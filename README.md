# K-Nearest-Neigbours
# Task 1
From sklearn.datasets load digits dataset and do following
1. Classify digits (0 to 9) using KNN classifier. You can use different values for k neighbors and
need to figure out a value of K that gives you a maximum score. You can manually try different
values of K or use gridsearchcv
1. Plot confusion matrix
2. Plot classification report

#Task 2
Use kNN to Predict the Age of Sea Slugs
Download the dataset from this link:
https://archive.ics.uci.edu/ml/datasets/abalone
This dataset contains age measurements on a large number of abalones.
The age of an abalone can be found by cutting its shell and counting the number of rings on the
shell. In the Abalone Dataset, you can find the age measurements of a large number of abalones
along with a lot of other physical measurements.
The goal of this task is to develop a model that can predict the age of an abalone based purely on
the other physical measurements. This would allow to estimate the abalone’s age without having
to cut its shell and count the rings. You’ll be applying kNN to find the closest prediction score
possible.
