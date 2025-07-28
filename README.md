# Nonparametric Approaches Assignment

## Overview
Implementation of nonparametric pattern recognition techniques:
- Parzen Window density estimation
- k-Nearest Neighbors (KNN) classification

## Assignment Tasks

### Question A: Parzen Windows 
1. Implement kernel functions:
   - Hypercube window
   - Gaussian window
2. Create Parzen density estimator:
   - Support both kernel types
   - Handle 1D data points
3. Optimize window width (h):
   - Compare estimated vs true N(0,4) likelihoods
   - Calculate MSE for h ∈ [0.2,10]
   - Plot MSE curves for both kernels

### Question B: KNN Classification
1. Implement core functions:
   - Euclidean distance calculator
   - k-nearest neighbors finder
2. Build KNN classifier:
   - Probability outputs for classes {0,1}
   - Handle 2D feature space
3. Parameter optimization:
   - Test k values: 1,3,5,...,15
   - Plot accuracy vs k
   - Visualize decision boundaries

## Technical Requirements
- Implemented in Google Colab (Python)
- Required datasets:
  - `dataA_Parzen.csv` (200 1D samples)
  - `dataB_KNNtrain.csv` (50 2D samples)
  - `dataB_KNNtest.csv` (50 2D samples)
