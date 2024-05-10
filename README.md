# House Prices - Advanced Regression Techniques
### dataset(https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
## Overview
This project aims to predict the final price of residential homes in Ames, Iowa, using advanced regression techniques. The dataset provided contains 79 explanatory variables describing various aspects of the homes, challenging participants to explore and utilize these features to accurately predict house prices.

## Problem Statement
Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. However, this dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence. The goal is to leverage the available data to build a predictive model that accurately estimates the final price of each home.

## Dataset Description
- The dataset contains 79 explanatory variables describing almost every aspect of residential homes in Ames, Iowa.
- Features include information about the size, quality, and condition of various components of the homes.
- The target variable is the final price of each home.

## Methodology
1. **Exploratory Data Analysis (EDA)**:
   - Explore the distribution of features and target variable.
   - Analyze correlations between features and identify patterns.

2. **Data Preprocessing**:
   - Handle missing values, outliers, and categorical variables.
   - Perform feature engineering to create new features or transform existing ones.

3. **Model Building**:
   - Select appropriate regression algorithms ( Linear Regression, Lasso,ridg).
   - Train multiple models and evaluate their performance using cross-validation.

4. **Hyperparameter Tuning**:
   - Tune hyperparameters of the best-performing models to optimize performance.

5. **Prediction and Evaluation**:
   - Make predictions on the test dataset using the trained model.
   - Evaluate model performance using appropriate metrics ( RMSE).

## Dependencies
- Python 
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Ridg
- lasso
- RandomForestRegressor


