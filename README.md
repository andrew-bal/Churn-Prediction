# Telco Customer Churn Exploratory Data Analysis and Prediction

**Introduction**

Enclosed is a Jupyter Notebook for the analysis of data about a telecommunication company’s customers. The notebook also uses machine learning models to predict which customers are likely to churn, i.e. discontinue using the company’s services. Such predictions can ultimately benefit both the customers and the company as well.


**Problem Statement**

Can we predict behaviour to retain customers? More specifically, can we predict which customer is likely to churn, utilising relevant customer data in order to develope focused customer retention programs? 


**Approach**

First, I conducted an exploratory data analysis to gain insight into the data and its structure. I also checked for missing data and potential mistakes in the dataset. Next, I prepared the data for the machine learning models. The dataset is moderately imbalanced, which is why I made decision to use ROC AUC scores and accuracy as metrics to evaluate the models, using stratified cross validation. I implemented several machine learning algorithms, including Naïve Bayes, Logistic Regression, K Nearest Neighbours, Support Vector Machine and Random Forest Classifiers. 

**Results**

I had the best result using a logistic regression classifier, which had an accuracy score of 80.3% and an ROC AUC score of 84.5%. 

