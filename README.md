# Real Estate Listing Price Prediction

This repository contains a comprehensive project aimed at predicting real estate listing prices using advanced machine learning techniques. The goal is to develop a robust model that accurately estimates property prices based on various features, facilitating better decision-making for buyers, sellers, and real estate professionals.

## Project Overview

The project is structured into two main phases:

1. **Data Preprocessing and Exploration**: In this phase, we clean and preprocess the dataset, handle missing values, encode categorical variables, and perform exploratory data analysis (EDA) to understand the relationships between features and the target variable (listing price).

2. **Model Development and Evaluation**: Here, we implement multiple machine learning models, fine-tune their hyperparameters, and evaluate their performance using appropriate metrics. The models include linear regression, decision trees, random forests, and gradient boosting algorithms.

## Key Features

- **Data Preprocessing**: Utilized techniques such as one-hot encoding and TF-IDF for categorical and textual data, respectively, to prepare the dataset for modeling.
<img width="868" alt="Screenshot 2025-01-23 at 2 02 32 PM" src="https://github.com/user-attachments/assets/21a76ccf-6852-46be-9a8c-f21d4b92169a" />

- **Feature Engineering**: Created new features and transformed existing ones to enhance model performance: used Google API to convert location features into coordinates.

- **Modeling**: Implemented and compared various machine learning models, including ensemble methods like XGBoost and CatBoost, to identify the best-performing model.

- **Hyperparameter Tuning**: Applied RandomizedSearch Cross-Validation to fine-tune model parameters for optimal performance.

- **Model Evaluation**: Assessed models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to determine their accuracy and reliability.

## Results

The final model demonstrated high accuracy in predicting real estate listing prices, outperforming baseline models and meeting the project's objectives. Detailed results and performance metrics are documented in the project notebooks.
