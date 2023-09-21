# Supply_Chain_Management


## Overview
This project focuses on improving the supply chain management of a Fast Moving Consumer Goods (FMCG) company, specifically in the instant noodles business. The company has identified a significant mismatch between demand and supply, leading to losses in inventory costs. The primary goal of this project is to optimize the supply quantity in each warehouse across the entire country.

## Goal
The primary objective of this project is to build a model using historical data to determine the optimal weight of products to be shipped from each respective warehouse. This will help the company better align supply with demand, reduce inventory costs, and ultimately improve profitability.

## Data Collection and Exploration:

Historical data related to the supply chain, including warehouse information, demand, and supply quantities, was collected and explored. This step involved data cleaning and preprocessing.

## Data Encoding:

Categorical variables in the dataset were encoded to numerical values, allowing machine learning algorithms to work with the data effectively.

## Data Splitting:

The dataset was split into training and testing subsets. The training data was used to build and train machine learning models, while the testing data was used to evaluate model performance.

## Model Selection:

Multiple machine learning algorithms were selected for the project, including Linear Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), k-Nearest Neighbors (k-NN), Gradient Boosting Regression, AdaBooster, and Bagging Regressor.

## Model Evaluation:

The performance of each model was evaluated using various metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) Score. These metrics provided insights into how well each model predicted supply quantities.


## Conclusion
The SCM project aims to optimize supply quantity based on historical data, reducing inventory costs, and improving profitability.
Multiple machine learning algorithms were evaluated, and the Gradient Boosting Regression model (with or without hyperparameter tuning) and the Bagging Regressor performed exceptionally well with low Mean Squared Error and high R-squared scores.
These models can help the FMCG company make more accurate decisions regarding the quantity of products to be shipped from each warehouse, ultimately improving their supply chain efficiency and reducing costs.
