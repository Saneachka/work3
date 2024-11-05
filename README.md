# Polynomial Regression on Insurance Dataset

This project demonstrates polynomial regression with Lasso and Ridge regularization on an insurance dataset to predict healthcare expenses. The process includes data preprocessing, feature scaling, polynomial feature expansion, and model evaluation.

Files
polynomial_regression_insurance.py: Main code file containing the full implementation of polynomial regression on the dataset.
Project Overview
The objective is to predict the insurance charges based on various factors like age, sex, BMI, children, smoker status, and region. We transform these features using polynomial expansion, then apply Lasso and Ridge regularization to enhance model performance and mitigate overfitting.

Steps
Data Loading and Preprocessing:

Load and explore the dataset.
Convert categorical variables into numerical ones.
Standardize features for better polynomial and regularization performance.
Polynomial Feature Expansion:

Expand the feature set to include polynomial terms up to the second degree.
Model Training and Evaluation:

Train linear regression, Lasso, and Ridge models on the polynomial feature set.
Evaluate models using metrics like R², Mean Absolute Error (MAE), and Mean Absolute Percentage Error (MAPE).
Visualization:

Plot predicted vs actual charges to visualize model accuracy on test data.
