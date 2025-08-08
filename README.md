# Pattern-recognition


The flow

#Operation on The Data

1) Read The Data:
 reading and preposses the data

2) Shuffling The Data:
We shuffled and randomized it to mix up data and can optionally retain logical relationships between columns.

3) Data Information and Describtion:
We used info() function to get information about the iris dataset, also we used describe() function to get the statistics information about the dataset such: Mean, count, minimum and maximum value of each feature and the standard deviation, These two function are built-in function applied in shuffled data.

4) Plot Labels:
it's an equal bar plots as each class has the same number of samples= 50, and plotting all samples of each class (relationship between all classes)

5)Split The Dataset:
We split the data into training and testing sets with 80% for training and 20% for testing.

6)Data Pre-processing:
We standraized/normalized the dataset with StandardScaler that get the mean and standard deviation of each sample and make the dataset in one range.




7) Feature Extraction:
We applied Principal Component Analysis (PCA) [Dimensionality Reduction] and reduced the dimensions into 2 components.

#ML 

8)Used Models:
We applied some machine learning models on the reduced data and for each model we get the confusion matrix and printed the training and testing accuracies.
Models such: Decision Tree, Naive Bayes, Random Forest, SVM and KNN.

9) Clustering Techniques:
Also we used some of clustering techniques that we studied in the course such K-Means and DBSCAN, and for each one print the cluser labels.

10) Prediction:
We predict 3 different samples with all used models and print the classes of each one.

11) Results:
Here are some results of accuracies of machine learning:
 
The accuracies changes by shuffelling.


