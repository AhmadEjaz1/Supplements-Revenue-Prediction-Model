# Supplements-Revenue-Prediction-Model
This project aims to predict revenue based on various business features (e.g., product categories, locations, platforms) using machine learning.
The goal is to help businesses:  Forecast future revenue accurately. 
Identify key drivers of revenue (e.g., high-performing products or regions).  Optimize resource allocation and marketing strategies
# Key Steps & Methodology
Data Preparation
Dropped irrelevant columns (e.g., Date).
Separated features (X) and target variable (Revenue).
Model Training
Linear Regression: Initially tested but showed systematic bias in residuals.
Random Forest Regressor: Achieved significantly better performance with near-zero residuals.
Performance Metrics
R² (R-squared): ~0.99 → Model explains 99% of revenue variance.
RMSE: ~0.05–0.1 (relative to revenue scale) → Extremely low prediction error.
Residual Analysis: Randomly scattered errors, confirming a robust fit.
Visual Diagnostics
Residual plots validated that the model avoids under/over-prediction trends.

# Results
# Linear Regression
![image](https://github.com/user-attachments/assets/6c5a0be0-49d7-49f7-b10e-e0e1309150fc)
![image](https://github.com/user-attachments/assets/c24806e3-984f-4a0d-8e4b-3790feb68312)
# Random Forest Regressor
![image](https://github.com/user-attachments/assets/30d10f9d-d739-4d2e-8742-bd2b9b8d5d33)
![image](https://github.com/user-attachments/assets/74514e73-9e48-4d8c-bd83-2b1e6d8e1637)
