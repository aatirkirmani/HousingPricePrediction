# HousingPricePrediction
Using Regularized Linear Regression to predict the sale price of the Houses.

## Table of Contents
* [Problem Statement](#problem-statement)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Methodology](#methodology)
* [Conclusions](#conclusions)
  
## Problem Statement:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

## Dataset:
The dataset contains data on 1460 house sales. Various features for each house such as Living Area, Basement(s), Total Rooms, SaleCondition etc. (81 features) are provided along with the target variable "SalePrice" referring to the sale price for that house.

## Technologies Used:
- Python 3.8.10
- Jupyter Notebooks
- Pandas 1.5.3
- Matplotlib 3.7.0
- Seaborn 0.11.1

## Methodology:
- Data Cleaning.
- EDA.
- Splitting the Data into Train and Test Sets.
- Using Ridge and Lasso Regression to regularize the model.
- Iteratively creating models and discarding features based on VIF.
- Validating the assumptions of Linear Regression on the final model.

## Conclusions:
- Top 5 predictor variables for the House Price:
  - TotRmsAbvGrd.
  - OverallQualCondMean.
  - Neighborhood_NridgHt.
  - FullBath.
  - Neighborhood_NoRidge.
