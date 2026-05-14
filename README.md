# Code-MultipleKernel
Our multiple kernel codes include multiple kernel dimensionality reduction and multiple kernel clustering. 

This is a companion repository to our papers:
**K. Li, G. Wu**, *Randomized Algorithms with Sparse Kernel Weights for Large-scale Multiple Kernel Dimensionality Reduction and Clustering*, Machine Learning.

**Toolboxes required**:
  - Statistics and Machine Learning Toolbox

## 📁 Repository Structure

```
Code-MultipleKernel/
│
├── MKL_DR_Sparse20260513/                  # Core algorithms for multiple kernel dimensionality reduction
│   ├── MyMain_Supervised20220203.m          # Main code for supervised learning
│   ├── MyMain_Unsupervised20220203.m        # Main code for unsupervised learning
│   ├── MyMain_Semisupervised20220203.m      # Main code for semi-supervised learning
│   ├── OurSparse_diffK_Precond.m            # Main solving function for Algorithm 7
│   ├── OurMethod_31_diffKernel.m            # Main solving function for Algorithm 4
│   ├── calM_diffKernel_Parallel.m           # Calculate correlation matrix between kernels (Algorithm 7)
│   ├── Nystrom_A_1_diffKernel.m             # Solve sample coefficient matrix A (Algorithm 7)
│   ├── UpdateWeight_diffK_Paral_ourKaczmarz_1.m   # Solve kernel weight vector β (Algorithm 7)
│   ├── Nystrom_A_diffKernel.m               # Solve sample coefficient matrix A (Algorithm 4)
│   ├── MYBlockREKcol_diffK_1_ourKaczmarz.m  # Solve kernel weight vector β (Algorithm 4)
│   ├── Exp5.2.1_weight.m                    # Plot kernel weights mean & std (Algorithm 6)
│   ├── MyMain_Supervised_RateVSDimen20260408.m   # Trade-off: recognition rate vs dimensionality (Figure 13)
│   │
│   ├── Exp5.2.1_gamma/                      # Impact of regularization parameter γ (Algorithm 7)
│   │   ├── Main_Supervised_gamma20221003.m  # Main code that demonstrates the impact of the regularization parameter
│   │   └── Plot_gamma.m                     # Main function that plots figures
│   │
│   ├── Exp2_STAC/                           # Statistical tests for superiority demonstration
│   │   ├── MyMain_Exp2_STAC.m               # Main statistical tests code.
│   │   └── Plot.m                           # Main function that plots Figures 7-8
│   │
│   ├── Exp2_Binary graph/                   # 2D/3D visualization of unsupervised results
│   │   ├── Main_binary_Unsupervised20220615.m 
│   │   ├── Plot_Scatter_2dimensionality.m   # Main function  that plots 2D  visualizations (Figure 9)
│   │   └── Plot_Scatter_3dimensionality.m   # Main function  that plots 3D visualizations (Figure 10)
│   │
│   ├── lib/                                 # Helper functions
│   └── 数据库/                              # Sample datasets
│
├── MKL_Clustering20260513/                  # Core algorithms for multiple kernel clustering
│   ├── MyMain20220701.m                     # Running code for multiple kernel clustering
│   ├── Demo_MKKM_OurCode20220701.m          # Demo code for Algorithm 8
│   ├── FinalValues_ours20220701.m           # Impact of regularization parameter γ (Algorithm 8)
│   ├── OurCode/                             # Main codes for Algorithm 8
│   │   ├── Our_MKKM.m                       # Main solving function for Algorithm 8
│   │   ├── Compute_betasTilde.m             # Solve kernel weight vector β in Algorithm 8
│   │   ├── Nystrom_A_1_diffKernel.m         # Solve cluster representation matrix H in Algorithm 8
│   │   └── calM_diffKernel_Parallel.m       # Calculate correlation matrix between kernels
│   ├── lib/                                 # Helper functions
│   └── dataset/                             # Sample datasets
│
└── README.md
```

# If you find these codes are useful, please cite our paper:  
K. Li, G. Wu, Randomized Algorithms with Sparse Kernel Weights for Large-scale Multiple Kernel Dimensionality Reduction and Clustering, Machine Learning.

📧 Contact

Any discussions or concerns are welcomed! Please contact me via:
like@xzhmu.edu.cn



