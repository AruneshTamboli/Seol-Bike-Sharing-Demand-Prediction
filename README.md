# Project Title : Seoul Bike Sharing Demand Prediction

## Google Collab link: 
https://colab.research.google.com/github/AruneshTamboli/Seol-Bike-Sharing-Demand-Prediction/blob/main/(Proponent_Ds)_Bike_Sharing_Demand_Prediction_2_Capstone_Project.ipynb

## Problem Description:

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## Approach Taken
1. Importing libraries
2. Exploratory Data Analysis
3. Extracting features from date
4. Model Building

* LINEAR REGRESION

* LASSO REGRESSION

* RIDGE REGRESSION

* DECISION TREE
* 
* GRADIENT BOOSTING

* RANDOM FORREST

* XGBOOST


## Model Summary

![image](https://user-images.githubusercontent.com/88345564/147151585-ae2c29c2-4875-4f42-a598-234c6c12fd53.png)


## Conclusions:


* As it was stated in the problem, rented bike count was low in 2017 untill november. That is when business took off and rented bike count started increasing.

* There was sharp increase in demand from the end of 2017 that too in winter season of the year. The demand however decrease at the end of 2018.

* bike count rent is highly correlated with 'Hour', which seems obvious. Demand for bike is mostly in morning (7 to 8) and in the evening (3 to 9).

* After doing exploratory data analysis, applying Linear Regression model didn't go quite well as it gave only 65% accuracy.

* Lasso and Ridge Regression helps to reduce model complexity and prevent over-fitting which may result from simple linear regression. with Lasso, ridge and ElsasticNet regressor We got r squared value of 0.64, 0.65, 0.68 respectively.
* With Decision tree we reached at the model r squared value of 0.80.

* Random forest regressor gave r squared value of 0.83 on test data.

*Gradient Boost gave r squared value of 0.91.

*XGBOOST came for the rescue to help us get best accuracy to approximate numbers of rented bikes demand. It gave amazing results of training r-square at 0.97 and test r-square value at 0.919 also with adjusted r-square with 0.918.
