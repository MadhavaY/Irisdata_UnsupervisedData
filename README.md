# Irisdata_UnsupervisedData
ML - Iris Flower Classifier
A lightweight introduction to machine learning in Rubix ML using the famous Iris dataset and the K Nearest Neighbors algorithm. By the end of this tutorial, you'll know how to structure a project, instantiate a learner, and train it to make predictions on some test data.

Difficulty: Easy
Training time: Less than a minute


Introduction
The Iris dataset consists of 50 samples for each of three species of Iris flower - Iris setosa, Iris virginica, and Iris versicolor (pictured below). Each sample is comprised of 4 measurements or features - sepal length, sepal width, petal length, and petal width. Our objective is to train a K Nearest Neighbors (KNN) classifier to determine the species of Iris flower from a set of unknown test samples using the Iris dataset. Let's get started!

Iris Flower Species

Extracting the Data
The first step is to extract the Iris dataset from iris.csv file in our project folder into our training script.It uses the last column of the data table for the labels and the rest of the columns for the values of the sample features. We'll call this our training set.

We are divding the data into x and y where x is petal length and y is petal width.
Now we are dividing the data into 4 clusters. Dividing the clusters into 4 is our choice.


Finally we are showing the data using plt.show()

