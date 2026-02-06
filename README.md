# PCA Implementation - Rwanda Ubudehe Livestock Data

Principal Component Analysis implementation from scratch using NumPy on Rwanda's Ubudehe Livestock dataset.

## About

This project implements PCA without using sklearn's PCA class, demonstrating the mathematical foundations of dimensionality reduction through eigendecomposition.

## Setup
```bash
git clone https://github.com/62Laura/pca-assignment.git
cd pca-assignment
jupyter notebook pca_assignment.ipynb
```

## Implementation

The notebook covers:

1. Data Preprocessing - Handling missing values and standardization
2. Covariance Matrix - Computing feature relationships
3. Eigendecomposition - Extracting eigenvalues and eigenvectors
4. Component Selection - Dynamic selection based on explained variance
5. Data Projection - Transforming data to lower dimensions
6. Visualization - Before/after comparisons and biplots
7. Benchmarking - Performance comparison with scikit-learn

## Results

Reduced dimensionality while retaining 95% of variance.
