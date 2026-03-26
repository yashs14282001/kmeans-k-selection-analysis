# Evaluating Methods for Choosing K in K-Means Clustering

## Overview
This project investigates how to determine the optimal number of clusters (K) in K-Means clustering. It compares two widely used methods: the Elbow method and the Silhouette score.

## Research Question
How can we determine the optimal number of clusters in K-Means clustering, and how reliable are the Elbow and Silhouette methods across different types of datasets?

## Datasets
Three datasets are used to evaluate performance:
- Well-separated clusters (ideal scenario)
- Overlapping clusters (challenging scenario)
- Non-spherical clusters (violates K-Means assumptions)

## Methods Used
- K-Means Clustering
- Elbow Method (WCSS)
- Silhouette Score

## Key Findings
- Elbow method works well for clearly separated clusters
- Silhouette score provides better insight for overlapping data
- Both methods struggle with non-spherical clusters
