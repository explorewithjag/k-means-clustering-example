# K-Means Clustering Example

Clustering is one of the most common exploratory data analysis techniques used to get an intuition about the structure of the data. It can be defined as the task of identifying subgroups in the data such that data points in the same subgroup (cluster) are very similar while data points in different clusters are very different.


__K-Means Algorithm__

Kmeans algorithm is an iterative algorithm that tries to partition the dataset into Kpre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. It tries to make the inter-cluster data points as similar as possible while also keeping the clusters as different (far) as possible. 

It assigns data points to a cluster such that the sum of the squared distance between the data points and the cluster’s centroid (arithmetic mean of all the data points that belong to that cluster) is at the minimum. The less variation we have within clusters, the more homogeneous (similar) the data points are within the same cluster.

The way the K-means algorithm works is as follows:
<ul>
  <li>Specify the number of clusters K.</li>
  <li>Initialize centroids by first shuffling the dataset and then randomly selecting K data points for the centroids without replacement.</li>
  <li>Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.</li>
  <li>Compute the sum of the squared distance between data points and all centroids. Assign each data point to the closest cluster (centroid).</li>
  <li>Compute the centroids for the clusters by taking the average of all data points that belong to each cluster.</li>
</ul>





In this series, you will learn how to create a K-Mean clustering model and Create Clusters to analyze your data.
Hope you have enjoyed learning this, if so share this with others and for more such contents you can connect with me on

YouTube: https://www.youtube.com/channel/UCmF8qppe02J1ot4Jfwl_lFg

LinkedIn: https://www.linkedin.com/in/jagwithyou/

Medium: https://medium.com/@jagwithyou
