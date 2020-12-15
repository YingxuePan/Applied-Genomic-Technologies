# K-Means-Intros, Algorithms, and Limitations


K-Means Clustering: 
1. Introduction
2. Algorithms
3. Implementations
4. Limitations and Advantages.

## 1.\ Introduction
**K-means clustering** is a **clustering** algorithm that partitions n objects into **k** groups in which each object belongs to the cluster with the nearest **mean** (aka. cluster centroid). In bioinformatics, K-means can be used to find the genes that share common expression patterns across different samples and the patients that share similar gene expression patterns, etc. We will show an example of the second application in the following sections. Compared to other clustering methods, K-means clustering can work with large datasets in an efficient runtime.

## 2.\ Algorithm
In a nutshell, K-means clustering begins with randomly selected centroids (graph b), assigns objects to the closest cluster (graph c), updates the centroids based on the current assignment of objects (graph d), and repeats the previous two steps (graph e and f) until it reaches convergence.
![Visualization of k-means algorithm](Group23Pics\kmeansalgo.png)
