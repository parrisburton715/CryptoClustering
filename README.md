# Cryptocurrency Market Data Clustering

## Overview

This project analyzes cryptocurrency market data using K-Means clustering and Principal Component Analysis (PCA). The goal is to identify clusters of cryptocurrencies based on their price change percentages over various time periods. The analysis includes data normalization, dimensionality reduction, clustering, and visualization.

## Dependencies

This project requires the following Python libraries:

- `pandas`: For data manipulation and analysis.
- `hvplot.pandas`: For interactive plotting with Pandas DataFrames.
- `scikit-learn`: For machine learning tasks, including clustering and dimensionality reduction.

## Usage

Data Preparation
Load Data: Read the cryptocurrency market data from a CSV file into a Pandas DataFrame.
Inspect Data: Display sample data and generate summary statistics.
Plot Data: Visualize the raw data to understand its structure.
Data Normalization
Normalize Data: Use StandardScaler to normalize the data, preparing it for clustering analysis.

## Clustering

Determine Optimal Clusters: Use the Elbow method to find the optimal number of clusters for K-Means clustering.
Cluster Data: Apply K-Means clustering to group cryptocurrencies based on their normalized price change percentages.

## Dimensionality Reduction

Apply PCA: Use Principal Component Analysis (PCA) to reduce the dimensionality of the data, making it easier to visualize and interpret.
Determine Optimal Clusters with PCA: Find the optimal number of clusters using the PCA-transformed data.
Cluster PCA Data: Apply K-Means clustering to the PCA-transformed data to identify clusters.

## Visualization

Scatter Plots: Create scatter plots to visualize the clustering results in both the original feature space and PCA-transformed space.
Elbow Curve: Plot the Elbow curve to determine the optimal number of clusters for both the original and PCA-transformed data.
Composite Plot: Combine visualizations to compare clustering results and the effectiveness of dimensionality reduction.

## License

This project is licensed under the MIT License - see the LICENSE file for details.