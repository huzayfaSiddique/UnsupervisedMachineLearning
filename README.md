 Unsupervised Machine Learning
===============================

Introduction
------------
Unsupervised Machine Learning is a type of machine learning where models are trained on unlabeled data. 
Unlike supervised learning, there is no target variables. Instead, the algorithm 
tries to find hidden patterns, groupings, or structures within the data on its own.

This approach is especially useful when labeled datasets are expensive, time-consuming, or impractical to obtain.

Use Cases
---------
Some common use cases of unsupervised learning include:
- Customer Segmentation: Grouping customers based on purchasing behavior.
- Anomaly Detection: Identifying unusual transactions in banking or fraud detection.
- Recommendation Systems: Suggesting similar products or content.

Famous Unsupervised Learning Algorithms
---------------------------------------

1. K-Means Clustering
   - Groups data into k clusters based on similarity. It assigns each data point to the nearest cluster center (centroid) 
     and updates the centroids iteratively.
   - Use case: Customer segmentation in marketing.

2. Hierarchical Clustering
   - Builds a hierarchy (tree-like structure) of clusters.Starts with each point as its own cluster and then merges clusters 
     step by step (agglomerative approach).
   - Use case: Document or gene similarity analysis.

3. DBSCAN 
   - Finds clusters based on data density. Groups closely packed points together and marks low-density 
     points as noise or outliers.
   - Use case: Detecting anomalies or finding clusters of irregular shapes.
