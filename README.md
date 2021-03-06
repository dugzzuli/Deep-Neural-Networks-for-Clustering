# Deep Learning Clustering with Tensor-Flow in Python;
In this report, we try to optimize an idea which already has been presented under title " Learning Deep Representations for Graph clustering" by F. Tian, B. Gao, Q. Cui, E. Chen, T. Liu. The idea is described as follows: “modeling a simple method which embedding the similarity graph by deep autoencoder with sparsity penalty, then runs the K-Means algorithm on the embedding graph to obtain the clustering result”. However, although our model is based on the original idea, but the graph similarity and the loss function and the model training methods are different. We also compare our results with the two previous results based on the recent papers ( F. Tian, B. Gao, Q. Cui, E. Chen, T. Liu, 2014), (S. Cao, W. Lu, Q, Xu, 2016) on the same datasets. 
Below you will see a autoencoder embedded 3NG(3 groups of the 20-newsgroups dataset)data into two dimensions:

![Alt text](https://github.com/saman-nia/Deep-Neural-Networks-for-Clustering/blob/master/Visualizations/2D_Embedded.png?raw=true "Title")


Here, you can see a visualization of Iris data set in n*n dimensions that after runnig the kmeans could get 1.00 score for NMI:

![Alt text](https://github.com/saman-nia/Deep-Neural-Networks-for-Clustering/blob/master/Visualizations/Similarity-3D.gif?raw=true "Title")
![Alt text](https://github.com/saman-nia/Deep-Neural-Networks-for-Clustering/blob/master/Visualizations/Similarity-kmeans.png?raw=true "Title")
