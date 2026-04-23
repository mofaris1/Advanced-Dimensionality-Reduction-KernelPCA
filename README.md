# Advanced Dimensionality Reduction: PCA vs. Kernel PCA

## Overview
This project explores advanced feature extraction and dimensionality reduction techniques. While standard Principal Component Analysis (PCA) is highly effective for linear data, real-world datasets often contain non-linear relationships. This project benchmarks standard PCA against **Kernel PCA (KPCA)** using multiple mathematical kernels to observe how non-linear mapping affects data separability and variance retention.

## Key Technical Achievements
1. **Variance Optimization:**
   - Evaluated the dataset to mathematically determine the optimal number of principal components.
   - Successfully reduced the feature space while retaining **95% of the cumulative variance** (requiring exactly 84 components).
2. **The Kernel Trick Implementation:**
   - Implemented standard linear PCA as a baseline.
   - Applied Kernel PCA using various functions to map data into higher-dimensional spaces before reduction:
     - **RBF (Radial Basis Function)**
     - **Polynomial (Poly)**
     - **Cosine**
     - **Linear**
3. **High-Dimensional Data Visualization:**
   - Developed a dynamic visualization pipeline using `matplotlib` to plot and compare multiple combinations of the top 5 principal components across all applied kernels.

## Technologies Used
- Python
- Scikit-Learn (`PCA`, `KernelPCA`)
- Matplotlib (Subplot grid visualizations)
- Pandas & NumPy
