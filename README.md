# Banglore-House-Price-Prediction
Banglore House Price Prediction - Machine Learning Project
# Table of Contents
1. Introduction
2. Dataset
3. Data Preprocessing
4. Feature Engineering
5. Models Used
6. Evaluation Metrics
7. Results
8. Conclusion
9. Future Work
10. References


# 1. Introduction
The Bangalore House Price Prediction project aims to predict the prices of houses in Bangalore using various regression models. This project involves data preprocessing, feature engineering, model training, evaluation, and comparison to identify the most effective model for predicting house prices.

# 2. Dataset
The dataset used in this project is sourced from Kaggle: Bengaluru House Price Data. It contains various features such as area type, location, size, total square feet, number of bathrooms, balcony count, and the price of the house.

# 3. Data Preprocessing
Data preprocessing steps include:

Handling missing values by dropping columns with a high percentage of missing data and filling missing values in columns with low percentages of missing data.
Converting categorical features to numeric using techniques such as one-hot encoding.
Scaling features using Min-Max scaling.
Detecting and removing outliers using methods like Z-score.

# 4. Feature Engineering
Feature engineering involves:

Converting the 'total_sqft' feature to a numeric format by handling ranges and non-numeric entries.
Extracting the number of bedrooms (BHK) from the 'size' feature.
Creating new features to enhance the predictive power of the models.

# 5. Models Used
Seven regression models were used in this project:
* Linear Regression: 
A basic regression model that assumes a linear relationship between the input features and the target variable.
* Lasso Regression: 
A linear model with L1 regularization to prevent overfitting by penalizing large coefficients.
* Ridge Regression:
Similar to Lasso, but uses L2 regularization.
* Random Forest Regression: 
An ensemble model that builds multiple decision trees and averages their predictions.
* Gradient Boosting Regression:
An ensemble model that builds trees sequentially, with each tree correcting errors made by the previous ones.
Support Vector Machine: A model that tries to find the hyperplane that best separates the data into different classes, adapted here for regression.
* XGBoost: 
An optimized version of gradient boosting that is efficient and effective for large datasets.
