# CryptoClustering

I would like to give my thanks to TA Drew for providing guidance through his speedruns.

I used unsupervised machine learning to determine if the price in cryptocurrencies change in short periods of time (1 day and 7 days).

I first attempted to use the KMeans method after scaling the data to cluster these cryptocurrencies based on their price changes in these short periods of time. In the four clusters, I noticed two of them only had
one member within them and that they both overlapped, so I also used PCA to simplify the data for improved clustering.

Almost all variance was accounted for in my PCA model (99.98%) so this may explain why my elbow curve could not produce an optimal k value (or the number of clusters) I should use when all inertias were the same regardless
of how many clusters I used. I ended up using four clusters again, which did separate the clusters much better and also illustrated how the outlier clusters behaved differently with short term price changes.

