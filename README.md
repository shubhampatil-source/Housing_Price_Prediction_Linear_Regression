# Ames House Price Prediction using Multiple Linear Regression

## Project Overview

This project develops and deploys a Multiple Linear Regression model to predict residential property prices using the Ames Housing Dataset. The solution combines exploratory data analysis, feature engineering, statistical validation, machine learning, and interactive deployment through Streamlit.

The objective is to identify the key drivers of housing prices and build an interpretable model that provides accurate property value estimates.

---

## Business Problem

Accurately estimating house prices is essential for buyers, sellers, real estate agents, and property investors. Property values are influenced by several factors such as construction quality, living area, neighborhood, and age of the property.

This project aims to:

* Identify the most influential factors affecting house prices.
* Quantify the impact of property characteristics on price.
* Build a predictive model for real-time house valuation.
* Deploy the model as an interactive web application.

---

## Dataset

Dataset: Ames Housing Dataset

The dataset contains detailed information about residential properties, including:

* Overall Quality
* Living Area
* Garage Area
* Year Built
* Neighborhood
* Sale Price

Total Records: 1,460+

---

## Project Workflow

### 1. Data Cleaning

* Removed unnecessary columns.
* Treated missing values.
* Handled categorical variables.

### 2. Exploratory Data Analysis

* Distribution analysis of Sale Price.
* Correlation analysis.
* Neighborhood-wise price comparison.
* Outlier identification and treatment.

### 3. Feature Engineering

Selected features:

Numerical:

* Overall Quality
* Total Living Area
* Garage Area
* Year Built

Categorical:

* Neighborhood

### 4. Data Transformation

* Log transformation applied on Sale Price.
* One-Hot Encoding for Neighborhood.
* Feature Scaling using StandardScaler.

### 5. Model Building

Algorithm:

* Multiple Linear Regression

### 6. Model Validation

Assumptions evaluated:

* Linearity
* Multicollinearity (VIF)
* Residual Normality
* Independence of Errors
* Homoscedasticity

### 7. Deployment

* Streamlit Web Application
* Interactive House Price Prediction Interface

---

## Model Performance

| Metric      | Value  |
| ----------- | ------ |
| R² Score    | 0.87   |
| Adjusted R² | 0.867  |
| MAE         | 16,577 |
| RMSE        | 22,430 |
| MAPE        | 10.21% |

---

## Key Insights

* Overall Quality is one of the strongest drivers of house prices.
* Larger living areas significantly increase property value.
* Newer homes generally command higher prices.
* Neighborhood location contributes substantially to pricing differences.
* The model explains approximately 87% of house price variation.

---

## Tech Stack

Python

Libraries:

* Pandas
* NumPy
* Scikit-Learn
* Statsmodels
* Matplotlib
* Seaborn
* Streamlit

---

## Future Improvements

* Compare with Ridge and Lasso Regression.
* Experiment with Random Forest and XGBoost.
* Add confidence intervals for predictions.
* Integrate Power BI dashboard.
* Enable batch predictions through file upload.

---

## Author

Shubham Patil

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning | GenAI
