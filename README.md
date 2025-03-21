# Credit-card-transaction-KMeans-clustering

## Overview

This project focuses on clustering credit card transactions using K-Means clustering. The dataset is preprocessed, normalized, and optimized using different techniques to identify the best clustering approach.

### Steps Involved

### 1. Data Import

The dataset is imported using read_csv().

### 2. Data Preprocessing

1. Handled missing values using SimpleImputer(strategy='median') for credit_limit and minimum_payments columns.

2. Performed feature engineering by combining relevant columns into a single meaningful feature.

3. Standardized the dataset using StandardScaler to normalize data distribution.

### 3. Model Training

1. Implemented K-Means clustering with k=3.

2. Evaluated clustering performance using the elbow method to determine the optimal number of clusters.

3. Used silhouette_score and davies-bouldin_score to assess cluster quality and refine the number of clusters.

4. Implemented KMeans++ to find the best clustering initialization method and improve performance.

### Results

1. The optimal number of clusters was determined using multiple evaluation metrics.

2. KMeans++ was compared with standard K-Means to find the best-suited clustering approach for this dataset.

### Future Enhancements

1. Implement additional clustering algorithms (DBSCAN, Agglomerative Clustering) for comparison.

2. Improve feature engineering techniques for better insights.

3. Deploy as a web-based visualization tool.
