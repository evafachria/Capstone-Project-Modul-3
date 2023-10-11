# Capstone-Project-Modul-3
Customer Lifetime Value Prediction With Machine Learning

This repository contains a machine learning project conducted for FunDrive Car Insurance to predict Customer Lifetime Value (CLV) in the context of car insurance. CLV is a crucial metric for understanding the value a customer brings to a business and helps in making decisions regarding customer retention, marketing efforts, and long-term business strategies.

## Business Problem:
FunDrive Insurance faces the challenge of predicting CLV accurately, as different factors contribute to determining CLV for car insurance clients. The company needs a machine learning tool to predict CLV and make informed decisions about customer retention strategies.

## Goals:
The goal of this project is to develop a machine learning model to predict CLV with low error rates, helping FunDrive Insurance avoid losses from inefficient retention costs and target valuable clients more effectively.

## Data Understanding:
The dataset includes customer information and features related to CLV, with both numerical and categorical data. There are no missing values, but there are duplicates, which are dropped. Outliers are present, but they are not removed to preserve information. Income values of 0 are associated with unemployed clients.

## Modeling:
Several regression models, including Gradient Boosting with Transformed Target Regression, are benchmarked using RMSE, MAE, and MAPE as evaluation metrics. The best model is selected based on its performance, and it is used for CLV prediction.

## Hyperparameter Tuning:
Grid search is employed to optimize hyperparameters, improving the model's performance. The RMSE, MAE, and MAPE values are reduced, indicating better predictive accuracy.

## Conclusion:
The best model is the Gradient Boosting Regressor with Transformed Target Regression. The MAPE is approximately 10.22%, indicating a high level of accuracy for CLV prediction within the trained range.

## Recommendations:

Increase the dataset with CLV values above 18,000 for better predictions.
Add additional features such as contract duration, cross-selling, and demographic factors to improve model significance.
Conduct A/B testing to assess real-world model effectiveness.
Schedule periodic model updates to adapt to changing data and customer trends.
Consider building advanced models using deep learning and real-time integration into the company's systems.
Implement retention and upselling strategies based on CLV insights, such as cross-selling additional insurance products or encouraging existing customers to upgrade their coverage.
This repository provides the code, data preprocessing, modeling, and evaluation of the CLV prediction model for FunDrive Car Insurance.

## Author
[EVA FACHRIA]

## Acknowledgments
Special thanks to [Ragil Hadi Prasetyo] for the help and insight.
