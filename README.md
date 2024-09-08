# CryptoClustering

## Overview

The CryptoClustering project applies machine learning techniques, specifically K-means clustering and Principal Component Analysis (PCA), to classify cryptocurrencies based on their price fluctuations across various timeframes. The project involves:

1. Loading and preparing cryptocurrency market data.
2. Scaling the data and using the Elbow method to find the optimal number of clusters (`k`).
3. Clustering cryptocurrencies using K-means on the original scaled data.
4. Performing PCA to reduce the feature space and finding the optimal number of clusters on PCA-transformed data.
5. Analyzing the influence of each feature on the principal components.

## Files

- `Crypto_Clustering.ipynb`: Jupyter notebook containing the code and analysis for clustering cryptocurrencies.

## Setup

 **Create a New Repository:**
   - Go to GitHub and create a new repository named `CryptoClustering`.
**Clone the Repository:**
   ```bash
   git clone https://github.com/dmmonjur/CryptoClustering.git





**Navigate to the Project Directory
   ```bash
   cd CryptoClustering
3. **Dependencies

Ensure you have the following Python libraries installed:
  ```bash
   pip install pandas scikit-learn matplotlib



Instructions

	Open the Notebook:
    	Launch Jupyter Notebook or JupyterLab.
    	Open Crypto_Clustering.ipynb.

	Run All Cells:
    	Execute each cell in the notebook to perform the analysis.

	Analyze Results:
    	Elbow Curve Analysis: Identifies the optimal number of clusters for both original and PCA-transformed data.
    	Clustering Results: Visualize the clusters based on price changes and PCA components.
    	PCA Analysis: Examine how features influence principal components.

Results

	Elbow Curve Analysis: The notebook plots the Elbow curve for both the original data and PCA-transformed data to determine the optimal k.
	Cluster Visualization: Scatter plots show clusters based on different features and principal components.
	PCA Analysis: The impact of PCA on dimensionality reduction and feature importance.



