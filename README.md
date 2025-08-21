## Project Overview

This project focuses on applying different regression techniques to the Algerian Forest Fires dataset. The main aim was to compare Linear Regression with regularization methods such as Ridge, Lasso, and ElasticNet, and to observe how they help in reducing overfitting and improving model performance.

## Dataset

Algerian Forest Fires dataset (publicly available).

Features include temperature, humidity, wind, and other environmental factors.


## Methodology

1. Performed basic data cleaning and feature selection.


2. Trained models using:

Linear Regression

Ridge Regression

Lasso Regression

ElasticNet Regression



3. Evaluated models with:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score



4. Compared residual plots to understand model fit.


5. Implemented cross-validation to ensure stable results.



## Results

Ridge and Lasso gave better generalization compared to plain Linear Regression.

ElasticNet worked well as a balanced approach between Ridge and Lasso.

Regularization helped reduce the impact of multicollinearity.


## What I Learned

The practical difference between Ridge, Lasso, and ElasticNet.

Why regularization is important when handling correlated features.

How to implement and compare models in Python using scikit-learn.


## Future Work

Extend analysis with Polynomial Regression and tree-based models.

Deploy the model with an interactive interface for easier use.


