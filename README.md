# Credit card defaulter

## Description:

This project aims to identify customers who are likely to default on credit card payments using a binary classification task. The classification is performed using a decision tree and an ensemble technique (Random Forest), based on independent features such as account type, loan taken, duration, and marital status.

The project utilizes the feature importance function of the Random Forest classifier to identify the most important features that have the most correlation with the target variable. The features identified as the most important are account duration, age, and account month.

One of the key challenges in using tree-based models is the issue of overfitting. This project demonstrates how an ensemble technique like Random Forest overcomes the issue of overfitting by combining multiple decision trees and reducing the variance of the model.

The project involves collecting and preprocessing data related to customer accounts and credit card payments, training and evaluating the decision tree and Random Forest models, and analyzing the feature importance results to identify the most relevant features. The outcome of the project is a reliable and accurate model that can be used to predict credit card payment defaults, helping the bank to manage credit risk and improve financial performance.


### Machine Learning Models:
1. Decision tree classifier 
2. Random Forest classifier

### Programing language:
1. Python

### Libraries:
1. Numpy
2. Pandas
3. Sklearn
4. Matplotlib
