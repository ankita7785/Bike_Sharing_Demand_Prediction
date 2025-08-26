# Bike_Sharing_Demand_Prediction
This project focuses on predicting bike rental demand using Multiple Linear Regression based on various environmental and demographic factors. The goal is to identify the key drivers of demand and build a predictive model to assist bike-sharing companies in resource allocation and demand planning.
✅ Objectives
Perform data cleaning and preprocessing to handle missing values and outliers.
Conduct Exploratory Data Analysis (EDA) to understand data distribution and feature relationships.
Build and validate a Multiple Linear Regression model for predicting demand.
Identify the most significant features affecting bike rentals.

🛠 Tech Stack
Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Environment: Jupyter Notebook

📊 Steps Performed
Data Understanding & Cleaning: Checked for null values, outliers, and corrected data types.
EDA:
Univariate Analysis: Histograms and boxplots for numerical features.
Bivariate Analysis: Correlation matrix, heatmaps, and pair plots.
Feature Engineering: Created dummy variables for categorical features and applied scaling.
Model Building:
Implemented Multiple Linear Regression using Scikit-learn.
Validated assumptions (VIF for multicollinearity, residual analysis for normality).
Model Evaluation:
Metrics: R², Adjusted R², RMSE.
Top predictors: registered users, casual users, temperature.
