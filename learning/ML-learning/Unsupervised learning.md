# **Unsupervised learning**



##### ***Finds patterns or groups in unlabeled data, like clustering or dimensionality reduction.***

##### 

Divided into three main categories :



**.Clustering**

**.Association Rule Mining**

**.Dimensionality Reduction**

&#x20;

### **1.Clustering**



***Clustering algorithms group data points into clusters based on their similarities or differences. Types of clustering algorithms are:***





###### **i. Centroid-based Methods:**



&#x20;

###### .K-Means clustering

&#x20;*K-Means Clustering groups similar data points into clusters without needing labeled data.*



###### .Elbow Method for optimal value of k in KMeans

*The Elbow Method is used to find the optimal number of clusters (k) in K-Means by analyzing how the clustering performance changes with different k values.*



###### .K-Means++ clustering

*K-Means++ is an improved version of the K-Means algorithm. Instead of picking all centroids randomly, it chooses the first center randomly and then selects the remaining centers in a spaced-out manner.*

###### 

###### .K-Mode clustering

*K-Modes uses the number of mismatches between categorical values to decide how similar two data points are.*



###### .Fuzzy C-Means (FCM) Clustering

*Fuzzy clustering allows each data point to belong to multiple clusters with different membership values.*





###### **ii. Distribution-based Methods:**





###### .Gaussian mixture models

*Gaussian Mixture Model assumes that the data is generated from a mixture of K Gaussian distributions, each representing a cluster.*



###### .Expectation-Maximization Algorithm

*The Expectation-Maximization (EM) algorithm is an iterative optimization technique used to estimate unknown parameters in probabilistic models, particularly when the data is incomplete, noisy or contains hidden (latent) variables.* 



###### .Dirichlet process mixture models (DPMMs)

*Dirichlet Process Mixture Models (DPMMs) is a flexible clustering method that can automatically decide the number of clusters based on the data.*





###### **iii. Connectivity based methods:**





###### .Hierarchical clustering

*Hierarchical Clustering is an unsupervised learning technique that groups data into a hierarchy of clusters based on similarity.* 



###### .Agglomerative Clustering

*Most common hierarchical clustering technique where each data point starts in its own group (cluster) and step by step the closest clusters are joined together until we reach one big cluster.* 



###### .Divisive clustering

*A type of hierarchical clustering It starts by placing all data points into one large cluster and then recursively splits that cluster into smaller ones based on differences or distances between the points.This process continues until each cluster contains only similar data points or meets a stopping condition.*



###### .Affinity propagation

*Affinity Propagation (AP) is a clustering algorithm that automatically identifies clusters and their exemplars (representative points) without requiring you to specify the number of clusters in advance.*





###### **iv. Density Based methods:**





###### .DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

*DBSCAN is a density-based clustering algorithm that groups data points that are closely packed together and marks outliers as noise based on their density in the feature space.*



###### .OPTICS (Ordering Points To Identify the Clustering Structure)

*OPTICS does not directly assign clusters but instead creates a reachability plot which visually represents clusters.* 





### **2. Dimensionality Reduction**





***Dimensionality reduction is used to simplify datasets by reducing the number of features while retaining the most important information.***



.Principal Component Analysis (PCA)

.t-distributed Stochastic Neighbor Embedding (t-SNE)

.Non-negative Matrix Factorization (NMF)

.Independent Component Analysis (ICA)

.Isomap

.Locally Linear Embedding (LLE)





### **3. Association Rule**





***Find patterns between items in large datasets typically in market basket analysis.***



###### .Apriori algorithm

*Apriori Algorithm is a data mining technique used to identify items that frequently appear together in large datasets.*



.Implementing apriori algorithm

.FP-Growth (Frequent Pattern-Growth)



**.ECLAT (Equivalence Class Clustering and bottom-up Lattice Traversal)**

*ECLAT stands for Equivalence Class Clustering and bottom-up Lattice Traversal. It is a data mining algorithm used to find frequent itemsets in a dataset.* 

