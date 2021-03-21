# KNN
In this problem, we have taken the standard MNIST handwritten digit dataset, and as usual, split it into training and testing data. Treated each image as a vector. For all the test images and have calculated the nearest neighbor from the training data, and report this label as the prediction. 

How accurate is this method?
This project was implemented and executed by applying KNN algorithm with recognition accuracy of around 91-93%.


What metric did you use for distance?
Euclidian distance. To classify an unknown instance represented by some feature vectors as a point in the feature space, the k-NN classifier calculates the distances between the point and points in the training data set


How fast/slow is your implementation? can you analyze the bottlenecks and speed things up?
for large training data sets, the process can be time consuming due to the distance calculation of each test sample to the training samples.We can speed up the distance calculation processs.


Any ideas on improving accuracy?
Training data is clustered in an unsupervised manner to find the ideal cluster setup to minimize the intra-class dispersion. Once the clusters are defined, an iterative method is applied to select some percentage of the data closest to the cluster centers and furthest from the cluster centers, 
we achieve fast k-nearest neighbor classiﬁer by reducing the
number of reference points that need to be considered in the distance computation. The reduction is achieved by clustering the data points ﬁrst, - using unsupervised clustering to ﬁnd a stable cluster setup, followed by selecting the closest
points and the furthest points, respectively.
