# CryptoClustering

## Georgia Tech Data Analytics Bootcamp - Module 19 Challenge

This week, we were challenged to find the appropriate number of clusters that can be found within crypto-currency data using a couple of different methods we learned in class. I standardized the numeric data to make everything exist on the same scale. For the first method, I had a loop create models to finding the k-means depending on the number of clusters as it iterated through the loop. I then graphed the number of clusters with their corresponding inertia values and picked the number of clusters that minimized both the number of clusters and inertia values (the 'elbow' of the graph). From there, I created a graph comparing the daily price change against the weekly price change for each cryptocurrency and had them grouped by predicted cluster.

For the next method, I used principal component analysis to identify the number of clusters this model would pick. I went through similar steps as I did with the first method and found the appropriate number of clusters. From here, I could compare the two models to see how different they were. In doing so, I found that the models selected the same number of clusters, though PCA proved to have more compact clusters than those of the original KMeans method. PCA compacts a few components into one, so this makes sense to me.
