# Project: Multivariate Linear Regression Model for Predicting Diabetes

## Overview
This project implements a multivariate linear regression approach to predict diabetes disease progression using clinical and physiological variables. The workflow includes correlation analysis, baseline model development, and performance optimization through stepwise feature selection.

## Table of Contents
1. Data Preparation
2. Correlation Analysis
3. Model Development Without Feature Selection
4. Model Development With Feature Selection
5. Results

## Data Preparation
The dataset contains 442 observations and 10 predictor variables, including age, BMI, blood pressure, and serum measurements. The target variable represents diabetes disease progression.

## Correlation Analysis
A correlation matrix and heatmap were generated to examine relationships between variables and identify multicollinearity. BMI, S5, and BP showed strong positive correlations with the target variable.

## Model Development Without Feature Selection
A multivariate linear regression model was trained using all available features.
- R² Score: 0.52
- Evidence of multicollinearity due to highly correlated predictors

## Model Development With Feature Selection
A forward stepwise regression approach based on statistical significance (p-value < 0.05) was applied.
Selected features:
- BMI
- S5
- BP
- S1
- SEX
- S2

## Results
The optimized model achieved a significant improvement in performance:
- Final Model Accuracy (R²): 87%
- Improved interpretability and reduced multicollinearity
- Identification of key predictors influencing diabetes progression

## Tools & Libraries
- Python
- Pandas
- Matplotlib, Seaborn
- Statsmodels
- Scikit-learn
