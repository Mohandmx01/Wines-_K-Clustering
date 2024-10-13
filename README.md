#Wine Clustering Project
Overview
This project aims to group similar wines using clustering algorithms, with a focus on using a weighted Euclidean distance metric to enhance clustering accuracy. The goal is to identify natural groupings of wines based on their chemical properties and characteristics.

Features
Clustering Algorithm: The project uses K-Means clustering to group wines.
Distance Metric: The weighted Euclidean distance metric is applied to calculate distances between wine samples, allowing for feature-specific importance.
Dataset: The project uses a wine dataset with multiple chemical properties such as Alcohol, Malic Acid, Ash, Magnesium, and more.
Visualization: Results of the clustering are visualized, and cluster statistics such as silhouette score are provided.
Implementation
Data Preprocessing:

The dataset is loaded, and features are standardized.
Important wine characteristics are used as input features for the clustering algorithm.
Weighted Euclidean Distance:

A custom distance metric is implemented to weigh specific features more heavily based on their importance.
Clustering:

K-Means is used to cluster wines into distinct groups.
Three clusters are generated, and key statistics like average feature values within each cluster are analyzed.
Evaluation:

The silhouette score is computed to evaluate cluster quality and separation.
Results are discussed with a focus on the performance of the distance-based clustering approach.
Clustering Results
The wines were grouped into three clusters based on their chemical characteristics:
Cluster 0: Wines with higher Alcohol and Proline content, lower Color Intensity.
Cluster 1: Wines with higher Malic Acid and Proanthocyanins content.
Cluster 2: Wines with higher Flavanoids, OD280/OD315, and Proline values.
A detailed analysis of each cluster's feature averages is provided in the notebook.
Requirements
Python 3.x
Libraries:
numpy
pandas
scikit-learn
matplotlib
seaborn
