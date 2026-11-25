# Unsupervised Learning with Scikit-Learn

## Overview
This repository explores **Unsupervised Learning** techniques using the famous Iris dataset. Unlike supervised learning (where the model is given the answers), unsupervised learning is tasked with discovering hidden patterns, groupings, and structures in unlabeled data.

## What's Covered:
1. **K-Means Clustering:** Grouping flowers based on mathematical distance to centroids. Used the **Elbow Method** to find the optimal number of clusters (K=3), proving the algorithm can discover species without labels.
2. **DBSCAN:** Density-based clustering. Explored how it handles outliers (noise) and non-linear shapes, and why it struggles when clusters overlap.
3. **Hierarchical Clustering:** Building a dendrogram (tree) to visualize the hierarchy of how data points merge together based on distance.
4. **PCA (Principal Component Analysis):** A linear dimensionality reduction technique. Squashed 4D data into 2D to visualize the data while maximizing variance.
5. **t-SNE (t-Distributed Stochastic Neighbor Embedding):** A non-linear Manifold Learning technique. Used to unroll complex high-dimensional data into 2D, creating highly separated visual clusters.

## Key Learnings
- **Unsupervised vs. Supervised:** Unsupervised models find patterns without an answer key.
- **The Elbow Method:** A visual way to determine the optimal number of clusters in K-Means by plotting inertia.
- **Linear vs. Non-Linear:** PCA is linear (straight lines), while t-SNE is non-linear (focuses on local neighborhoods).
- **t-SNE Warning:** While t-SNE creates beautiful, separated visual clusters, it is strictly for visualization and cannot be used to transform new, unseen data.

## Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
