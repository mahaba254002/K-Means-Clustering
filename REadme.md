# K-Means Clustering

- Unsupervised machine learning algorithm used for clustering/partitioning data points into k distinct,non overlapping clusters
- *Each Observation belong to a cluster with the nearest mean*

## Objective of Kmeans Clustering
- Main objective is to minimize the **total within cluster variation** across all k-clusters


### Finding K-clusters
- You can use the elbow method As I have used on tghe iris dataset
- Conventionally, you can follow the following steps

1. Select the number of cluster(k) you need
2. Randomly select distinct datapoints based on k these will serve as centroids
3. Measure distance between 1st datapoint and the clusters
4. Assign the 1st point to the nearest cluster
5. Calculate mean value between 1st point and its nearest cluster,Assign the new mean.
6. Again repeat step 3 and 4 with different points
7. Repeat the process until mean value does not change