# Health Insurance Cost Prediction

This project builds a machine learning model to predict healthcare costs for insurance customers.

## Objective

Health insurance companies need to estimate the expected medical costs of customers.  
Accurate predictions help companies design better insurance plans and help customers plan their healthcare expenses.

## Dataset

The dataset contains demographic and health-related information about insurance customers.

Features:

age → age of the customer  
sex → gender  
bmi → body mass index  
children → number of dependents  
smoker → smoking status  
region → residential region

Target:

charges → medical costs billed by health insurance

## Method

A regression model is used to estimate healthcare costs.

Workflow:

1 Load dataset  
2 Encode categorical variables  
3 Train regression model  
4 Evaluate performance using Mean Absolute Error  
5 Predict costs for new customers using a validation dataset

## Model

Linear Regression

## Libraries

pandas  
numpy  
scikit-learn  
matplotlib  
seaborn
