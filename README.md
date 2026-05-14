# Code-MultipleKernel
Our multiple kernel codes include multiple kernel dimensionality reduction and multiple kernel clustering. 

This is a companion repository to our papers:
K. Li, G. Wu, Randomized Algorithms with Sparse Kernel Weights for Large-scale Multiple Kernel Dimensionality Reduction and Clustering, Machine Learning.

**Toolboxes required**:
  - Statistics and Machine Learning Toolbox

# Repository content

Code-MultipleKernel/
├── MKL_DR_Sparse20260513/                         # Core algorithms for multiple kernel dimensionality reduction.
│   ├── MyMain_Supervised20220203.m                # Main code for supervised learning.
│   ├── MyMain_Unsupervised20220203.m              # Main code for unsupervised learning.
│   ├── MyMain_Semisupervised20220203.m            # Main code for semi-supervised learning.
│   ├── OurSparse_diffK_Precond.m                  # Main solving function for Algorithm 7.
│   ├── OurMethod_31_diffKernel.m                  # Main solving function for Algorithm 4.
│   ├── calM_diffKernel_Parallel.m    #  Main function in Algorithm 7 for calculating the correlation matrix between kernel matrices.
│   ├── Nystrom_A_1_diffKernel.m                      # Main function in Algorithm 7 for solving the sample coefficient matrix $A$.
│   ├── UpdateWeight_diffK_Paral_ourKaczmarz_1.m      #  Main function in Algorithm 7 for solving the kernel weight vector $\bm{\beta}$.
│   ├── Nystrom_A_diffKernel.m                        #   Main function in Algorithm 4 for solving the sample coefficient matrix $A$.
│   ├── MYBlockREKcol_diffK_1_ourKaczmarz.m           #  Main function in Algorithm 4 for solving the kernel weight vector $\bm{\beta}$.
│   ├── Exp5.2.1_weight.m       # Main function that plots the mean values of the kernel weights and the standard deviations learned by Algorithm 6.
│   ├── MyMain_Supervised_RateVSDimen20260408.m      # Main function that demonstrates the trade-off between recognition rates and  dimensionality.
│   ├── Exp5.2.1_gamma/      #  Core algorithms that demonstrate the impact of the regularization parameter $\gamma$ used in Algorithm 7.
│   │   ├── Main_Supervised_gamma20221003.m          # Main code that demonstrates the impact of the regularization parameter.
│   │   └── Plot_gamma.m                 #  Main function that plots figures.
│   ├── Exp2_STAC/                      # Core algorithms using statistical tests to demonstrate the superiority of the proposed algorithms.
│   │   ├── MyMain_Exp2_STAC.m          #  Main statistical tests code.
│   │   └── Plot.m                      #  Main function that plots Figures 7-8.
│   ├── Exp2_Binary graph/              # Core algorithms that intuitively display the unsupervised results by the 2D and 3D visualizations.
│   │   ├── Main_binary_Unsupervised20220615.m          # Main code for 2D and 3D visualizations.
│   │   ├── Plot_Scatter_2dimensionality.m              #  Main function  that plots 2D  visualizations (Figure 9).
│   │   └── Plot_Scatter_3dimensionality.m              #  Main function  that plots 3D visualizations (Figure 10).
│   ├── lib/                     #   Helper functions.
│   └── 数据库/                   # Sample datasets.
├──  MKL_Clustering20260513/                 # Core algorithms for multiple kernel clustering.
│   ├── MyMain20220701.m                     # Running code for multiple kernel clustering.
│   ├── Demo_MKKM_OurCode20220701.m          #  Demo code for Algorithm 8. 
│   ├── FinalValues_ours20220701.m           #  Main code that illustrates the  impact of the regularization parameter $\gamma$ on Algorithm 8.
│   ├── OurCode/                             #   Main codes for Algorithm 8. 
│   │   ├── Our_MKKM.m                       # Main solving function for Algorithm 8.
│   │   ├── Compute_betasTilde.m             #  Main function in Algorithm 8 for solving the kernel weight vector $\bm{\beta}$.
│   │   ├── Nystrom_A_1_diffKernel.m         #  Main function in Algorithm 8 for solving the cluster representation matrix $H$.
│   │   └── calM_diffKernel_Parallel.m       #  Main function in Algorithm 8 for calculating the correlation matrix between kernel matrices.
│   ├── lib/                                 #   Helper functions.
│   └── dataset/                             # Sample datasets.
└── README.md

# If you find these codes are useful, please cite our paper:  
K. Li, G. Wu, Randomized Algorithms with Sparse Kernel Weights for Large-scale Multiple Kernel Dimensionality Reduction and Clustering, Machine Learning.

# Any discussions or concerns are welcomed! Please contact me via e-mail: like@xzhmu.edu.cn. 


