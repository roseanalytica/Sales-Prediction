# Sales Prediction: Leveraging Machine Learning for Retail Success

## Overview
This project is a data science endeavor aimed at predicting product sales in Big Mart outlets. Leveraging a dataset from Analytics Vidhya (source: [Analytics Vidhya Dataset]((https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/)) ), we've constructed a predictive model to forecast sales based on various features such as item identifiers, product categories, store locations, and more.

## Dataset
The dataset comprises information on 8523 products across 1559 stores, including attributes like item weight, visibility, maximum retail price (MRP), and outlet details. The primary goal is to develop an accurate machine learning model that can provide sales predictions for different products and outlets.

## Data Preprocessing
To prepare the data for modeling, we conducted several data preprocessing steps:

Removed duplicates to ensure data integrity.

*   Handled missing values using interpolation and forward fill techniques.
*   Ensured consistency in categorical data, addressing inconsistencies in item fat content.
*   Explored and visualized data distributions, correlations, and anomalies.

## Modeling
Two different regression models were employed for sales prediction:

1. Linear Regression Model:

Utilizes the Linear Regression algorithm for predicting sales.
Evaluated using R-squared (R²) and Root Mean Square Error (RMSE).

2. Regression Tree Model:

Implemented a Decision Tree Regressor for sales forecasting.
Evaluated using R-squared (R²) and Root Mean Square Error (RMSE).

## Results
We compared the performance of both models to determine the best choice for sales prediction. The recommendation is based on the model with the highest R-squared and lowest RMSE, indicating a better fit and accuracy.
