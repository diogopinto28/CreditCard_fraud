# Credit Card Fraud Prediction #

Dataset taken from Kaggle: https://www.kaggle.com/mlg-ulb/creditcardfraud

# Context
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

# Content
The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

# Objectives

Treat the data to run into ML models to predict a Score given the features (V1..V28, Time and Amount). Since the data is not balanced, only 492 frauds out of 248,807 transactions. I will use various options to balance the dataset and run several algorithms after to understand what is best for this particular case!

## Until now I only managed to do 1 technique (Undersampling) and apply 2 models to the dataset. As soon as I'm able to get time to do more I will update the repo ##

# References:
 - Hands on Machine Learning with Scikit-Learn & TensorFlow by Aurélien Géron (O'Reilly). CopyRight 2017 Aurélien Géron
 - https://towardsdatascience.com/having-an-imbalanced-dataset-here-is-how-you-can-solve-it-1640568947eb
 - https://www.analyticsvidhya.com/blog/2017/09/common-machine-learning-algorithms/
