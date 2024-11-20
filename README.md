Building a Model: k-Nearest Neighbors
The 'k' in k-nearest neigbors indicate that instead of using only the closest neighbor to classify a new data point,
we can consider any fixed number of k neighbors in the training fit.

All machine learning models in scikit-learn are implemented in their own classes, called Estimator classes.
The k-nearest neighbors classification algorithm is implemeted in the KNeighborsClassifier class in the neighbors module.

Before we can use the model, the class needs to be instantiated into an object - this whenthe value of k is set.

The knn object encapsulates the algorithm that will be used to build the model from the training data, as well as the algorithm to make predictions on new data points. It will also hold the the information that the algorithm has extracted from the training data

To build the model on the training set, we call the fit method of the knn object
This takes as arguments the NumPy array x_train - the training data and the NumPy array y_train - corresponding training labels.
