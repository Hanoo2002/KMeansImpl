# Dimensionality Reduction and Clustering Assignment

## Objectives

The objectives of this assignment are as follows:

- Introducing dimensionality reduction through PCA.
- Introducing Clustering through K-means.
- Correct Implementation of PCA and K-Means.
- Evaluate the impact of dimensionality reduction on clustering results.

## Problem Statement

Given the Breast Cancer Wisconsin (Diagnostic) dataset, the objective is to perform unsupervised clustering to identify inherent patterns or groupings within the dataset. This dataset contains features computed from digitized images of fine needle aspirates (FNAs) of breast masses, aiming to distinguish between malignant and benign tumors.

## Assignment Details and Requirements

1. **Implement K-Means using NumPy.**
2. **Implement PCA using NumPy.**
3. **Two Experiments:**
   - **First Experiment:**
     - Cluster the dataset using k-means.
   - **Second Experiment:**
     - Apply PCA, then cluster the dataset using k-means.
   - **Note:**
     - Make sure you don’t use the labels in both experiments.
4. **In Both Experiments:**
   - Apply the elbow method to find the best Number (local minimum) of k clusters (lecture P17).
   - Compare between the sum of square errors/distances in both experiments.
   - Add your notes in both experiments.
5. **In the Second Experiment:**
   - Experiment with different numbers of principal components.
   - Visualize the results and compare them with the original labels.
