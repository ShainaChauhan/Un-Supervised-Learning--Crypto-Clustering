# Cryptocurrency Clustering Project

## Overview
This project aims to cluster cryptocurrencies using K-Means clustering algorithm to identify patterns and group similar cryptocurrencies together. We employ Principal Component Analysis (PCA) to optimize clustering by reducing feature dimensions while preserving the essence of the dataset.

## Dependencies
- Python 3.7+
- Pandas
- Scikit-learn
- hvPlot
- PCA (Principal Component Analysis)

## Data Preparation
Data is normalized using `StandardScaler` to ensure uniformity, making it suitable for machine learning models.

## Clustering Cryptocurrencies
We perform K-Means clustering on:
1. Original Data: Direct application of K-Means to understand the natural groupings within the cryptocurrency market data.
2. PCA-Optimized Data: Applying PCA to reduce dimensions before clustering, aiming for optimized performance.

## Findings
- **Elbow Method**: Used to determine the optimal number of clusters (k). Identical elbow curves were observed for both datasets, suggesting a consistent optimal k-value across different feature dimensions.
- **Performance Enhancement**: PCA optimization led to a more defined clustering, especially notable in certain cryptocurrency clusters which became tighter and more distinct.

## Visualization
Scatter plots and elbow curves are provided to visually compare the clustering results and the effect of dimensionality reduction through PCA.

## Conclusion
The analysis concludes that employing PCA for dimensionality reduction not only retains essential clustering characteristics but also enhances the model's performance by providing clearer, more distinct clusters.
