This repository contains code and analysis for applying dimensionality reduction techniques (PCA and t-SNE) on the MNIST dataset.


Dimensionality reduction reduces the number of input features while retaining most of the information. We applied PCA to reduce the dataset from 784 to ~150 features and compared the performance of a Random Forest classifier on both the original and reduced datasets.

-->>Steps
1. Load and preprocess the MNIST dataset.
2. Apply PCA to retain 95% variance.
3. Visualize data using t-SNE.
