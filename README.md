# CryptoClustering
Module 19 Challenge

## Questions answered throughout the analysis

*What is the best value for k?*

Based on the elbow method, the best value for k would be between 3 or 4 since those values fall on the curve. 4 seems like the best fit since it is the peak of the curve before it begins to flatten out. 


*What’s the total explained variance of the three principal components?*

The total explained variance of the three principal components would be about 89.5%. This is found by taking the sum of the three principal components and converting to percent.


*What’s the best value for k when using the PCA data? Does it differ from the best value for k that you found by using the original data?*

The best value for k when using the PCA data is 4. It does not differ from the best value that was found using the original data.


*Based on visually analyzing the cluster analysis results, what’s the impact of using fewer features to cluster the data by using K-means?*

By using fewer features, the complexity and dimensionality of the data is reduced which leads to a simpiler visualization. This can make it easier to examine, however results in loss of information. Using fewer features can lead to less comprehensive clustering results due to loss in information. Some relationships/patterns of clusters may be lost. As we can see above, the clustering images do not align like the elbow curves do. Also with using fewer features, there may be increased sensitivity to the remaining features. This means that those features will have a stronger impact on clustering results. While this can make it easier to identify patterns, it can also be misleading if features were over reduced.


## Visuals of Elbow Curves and Clusters

The top graphs for both the elbow curve plots and cluster plots are from the original data while the lower graphs are from the pca analysis. 

![Comparison of Elbows](https://github.com/maderamel/CryptoClustering/blob/34f0196f1c2130b5d680c328332272de3ad531db/Resources/elbowComparison.png)

![Comparison of Clusters](https://github.com/maderamel/CryptoClustering/blob/34f0196f1c2130b5d680c328332272de3ad531db/Resources/clusterComparison.png)