# Project Title
Customer Churn Analysis
# Problem Statment 
Predicting customer churn is critical for telecommunication companies to be able to effectively retain customers. It is more costly to acquire new customers than to retain existing ones. For this reason, large telecommunications corporations are seeking to develop models to predict which customers are more likely to change and take actions accordingly.

In this project, we build a model to predict how likely a customer will churn by analyzing its characteristics:

(1) demographic information

(2) account information

(3) services information.

The objective is to obtain a data-driven solution that will allow us to reduce churn rates and, as a consequence, to increase customer satisfaction and corporation revenue.

# Dataset : Churn.csv
The data set used in this project is available on Kaggle and contains nineteen columns (independent variables) that indicate the of the clients of a fictional telecommunications corporation. The Churn column (response variable) indicates whether the customer departed within the last month or not. The class No includes the clients that did not leave the company last month, while the class Yes contains the clients that decided to terminate their relations with the company. The objective of the analysis is to obtain the relation between the customer’s characteristics and the churn.

# What is the software requirement?
Python 3.7 or above

# What are the required python packages?
Pandas 1.0.1
scikit-learn
scipy
numpy
matplotlib

# Exploratory Data Analysis and Data Cleaning
Exploratory data analysis consists of analyzing the main characteristics of a data set usually by means of visualization methods and summary statistics. The objective is to understand the data, discover patterns and anomalies, and check assumptions before performing further evaluations.
- Missing values and data types
- Remove customerID column
- Payment method denominations

# Feature Engineering
Feature engineering is the process of extracting features from the data and transforming them into a format that is suitable for the machine learning model. In this project, we need to transform both numerical and categorical variables. Most machine learning algorithms require numerical values; therefore, all categorical attributes available in the dataset should be encoded into numerical labels before training the model. In addition, we need to transform numeric columns into a common scale. This will prevent that the columns with large values dominate the learning process. The techniques implemented in this project are described in more detail below. All transformations are implemented using only Pandas; however, we also provide an alternative implementation using Scikit-Learn. As you can see, there are multiple ways to solve the same problem 😃.
# Steps done
-Label Encoding
- One-Hot Encoding
- Normalization
- Setting a baseline
- Splitting the data in training and testing sets
- Assessing multiple algorithms : 
In this project, we compare 6 different algorithms, all of them already implemented in Scikit-Learn.

Dummy classifier (baseline) K Nearest Neighbours Logistic Regression Support Vector Machines Random Forest Gradiente Boosting
- Algorithm selected: Gradient Boosting
- Hyperparameter tuning
- Performace of the model

# Drawing conclusions — Summary
In this post, we have walked through a complete end-to-end machine learning project using the Telco customer Churn dataset. We started by cleaning the data and analyzing. Then, to be able to build a machine learning model, we transformed the categorical data into numeric variables (feature engineering). After transforming the data, we tried 6 different machine learning algorithms using default parameters. Finally, we tuned the hyperparameters of the Gradient Boosting Classifier (best performance model) for model optimization, obtaining an accuracy of nearly 80% (close to 6% higher than the baseline).

#Tutorial video 
https://youtu.be/mdUIq1vYL5Y
