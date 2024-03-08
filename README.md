# Used Car Price Prediction

This repository contains a machine learning project for predicting used car prices. The goal is to develop a reliable model that can estimate the price of a used car based on various features such as power, kilometer, fuel type, and more.

## Overview

The project involves the following steps:

1. **Data Cleaning:** The dataset is thoroughly cleaned, including handling missing values, converting columns from German to English, and removing outliers.

2. **Feature Engineering:** Several features are engineered, including grouping brands and models, creating age bins, and replacing models with popularity scores.

3. **Data Visualization:** Univariate and bivariate analyses are performed to explore the distribution of features and their relationships with the target variable (price).

4. **Data Preprocessing:** The data is split into training, validation, and test sets. Numerical columns are scaled, and categorical variables are encoded.

5. **Model Selection:** Different regression models, including Linear Regression, Ridge Regression, Lasso Regression, and XGBoost Regression, are applied to the dataset.

6. **Model Evaluation:** The models are evaluated based on Mean Squared Error and R^2 Score.

7. **Cross-Validation:** Cross-validation is performed to obtain a more reliable estimate of the model's performance.

8. **Prediction:** The final XGBoost model is applied to new data to predict used car prices.

## Files

- `car_price_prediction.ipynb`: Jupyter Notebook containing the complete code and analysis.
- `car_data.csv`: Dataset used for training and evaluation.


