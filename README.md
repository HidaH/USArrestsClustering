# Clustering Analysis on US Arrests Dataset

In this project, we perform clustering analysis on the US Arrests dataset using Python. 
We use two popular clustering algorithms: KMeans and Hierarchical Clustering.

## Dataset

The US Arrests dataset contains crime statistics for all US states in 1973, including the number of murders, assaults, and rapes per 100,000 inhabitants. 
We will use this dataset to cluster the US states based on their crime statistics.

## KMeans Clustering

In the KMeans clustering algorithm, we first select the number of clusters `k` and then assign each data point to the closest centroid.

We use the elbow method to select the optimal value of `k`.

We implement KMeans clustering on the US Arrests dataset using the `KMeans` class from the `sklearn.cluster` module. 

## Hierarchical Clustering

In Hierarchical Clustering, we start with each data point as a separate cluster and then iteratively merge the closest clusters until we have a single cluster. 

We can use agglomerative divisive clustering. We visualize the dendrogram to select the optimal number of clusters.

We implement Hierarchical Clustering on the US Arrests dataset using the `AgglomerativeClustering` class from the `sklearn.cluster` module.

## Conclusion

We have performed clustering analysis on the US Arrests dataset using KMeans and Hierarchical Clustering. 
We found that both algorithms produced similar results and grouped the US states into three distinct clusters: high crime rate, moderate crime rate, and low crime rate. 
This analysis can provide valuable insights into the crime patterns of different US states and aid in the development of crime prevention strategies.
