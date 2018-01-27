# CSX_450_1_project_2


# Domain of the Problem
The dataset used for this problem is from the UC Irvine Machine Learning Repository. The repository can be found here (http://archive.ics.uci.edu/ml/datasets/seeds).

The dataset is about seeds from three different varieties of wheat: Kama, Rosa, and Canadian. The dataset contains 70 elements in each group which were randomly selected. A soft X-ray technique was used to obtain a visualzation of the internal strucutre of the seed kernal. 


# Problem Statement

For this problem we will aproach it using unsupervised learning. We will use k-means to cluster. We are trying to understand the relationship between the type of wheat and the physical attributes. 


# Dataset Description

The dataset takes up 10 KB in memory. It has 210 rows and 8 columns. The dataframe will have a dimension of 210 by 7 columns (one column is droped since it is a label). 
Data Types: Columns = Float
Target: n/a


# Solution

The solution will be a Kmeans cluster or a Guassian Mixture Model. 


# Benchmark Model
n/a

# Performance Metric
To measure the success of our model we will use a Silhouette score or a Dunn indes. 