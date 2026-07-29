# Medical Insurance Cost Prediction

A regression project predicting medical insurance costs based on personal and demographic factors. This project covers the full machine learning workflow from exploratory data analysis to model comparison and feature importance analysis.

## Project Overview
- **Type**: Regression (predicting insurance charges)
- **Models used**: Linear Regression, Random Forest Regressor
- **Evaluation metrics**: MSE, MAE, RMSE, R2 Score

## What is covered
- Exploratory Data Analysis (info, describe, missing value check)
- Visual EDA using histograms and correlation heatmap
- One-Hot Encoding of categorical columns (sex, smoker, region)
- Feature scaling using StandardScaler
- Train/Test split (80/20)
- Training and comparing Linear Regression and Random Forest models
- Feature importance analysis

## Key Results
- **Winning Model**: Random Forest
- **Top Feature**: Smoker status (smoker_yes), by far the strongest driver of insurance cost

## Dataset
Medical Insurance Cost Prediction dataset from Kaggle (M Rahul Vyas), containing personal details like age, sex, BMI, number of children, smoker status, region, and insurance charges.

## Tools Used
Python, pandas, numpy, seaborn, matplotlib, scikit-learn
