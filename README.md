# FraudDetection
## Objective
Make a prediction model with a binary classifier problem using Logistic Regression,Random Forest,SVM, XGBClassifier and AdaBoostClassifier
## Problem statement
The increase of online shopping and payments is the cause of financial fraud cases such as credit card fraud transaction. It becomes a challenging issue for most of giant companies to make a secure system for customers from fraud. Here comes the role of Machine learning algorithms to solve such real-world problems. This is actually a binary classification problem as we have to predict only 1 of the 2 class labels. This project shows some of Machine learning algorithms such as Logistic regression, Random Forest, SVM, XGBClassifier and AdaBoostClassifier for the prediction purpose. 

## Dataset
### Link [visit Kaggle website](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

Basically, the dataset is an imbalance dataset where number of Genuine cases are more than 99% and Fraud cases are nearly 2% of dataset. Have applied SMOTE method for class balancing. Having with balanced and imbalanced properties, the result has compared for both the cases.

***
## Result-Imbalanced dataset
![fig 1](https://github.com/dnchinmayee/FraudDetection/assets/51435468/404f7723-8ad3-4403-afc1-62775b849ad1)
## Result-Balanced dataset
![fig2](https://github.com/dnchinmayee/FraudDetection/assets/51435468/b4d22279-a6bb-431b-a7a2-295ee2c59c6b)

##Result Analysis

Comparing results for both the cases, the result shows RandomForest and Boosting algorithms always gives a good accuracy score. Class 0 is the label for Genuine cases and class1 is the label for Fraud cases. Comparing result RandomForest: for Imbalanced dataset the recall value of Fraud cases is 0.74 while for balanced dataset the recall value became 0.85 and the accuracy score remains same as 0.99. It shows the Recall value has increased as compared to 0.74 after applying SMOTE method. Like this we can compare the result for rest of the methods.

*** Happy Learning ***

