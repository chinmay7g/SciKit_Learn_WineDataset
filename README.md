# SciKit_Learn_WineDataset

Learnt and implemented the Custom Classifier on the wine dataset.
The problem statement defined for this particular repositroy is to always predict the majority class of the 
training data. The code is further extended to calculate the individual probability of classifying a new test point
into a particular category.

Dataset was imported using sklearn.datasets

Class MajorityClassifier was created by inhereting the BaseEstimator, and ClassifierMixin.

The class included fit, predict, predict_probabilities functions.
