# House price project
This project is an assignment where in I built a model for the prediction of demand for house price.

## Information
Name: Le Thuc Anh
Email: thucanhle149@gmail.com

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual testues and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below. 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual testue of the prospective properties and decide whether to invest in them or not.

The company wants to know:

- Which variables are significant in predicting the price of a house, and

- How well those variables describe the price of a house.


## Conclusions
Best model: Ridge regression

Final R Squared:
- Train set: 0.92
- Test set: 0.88

After doing the analysis, which contains EDA, Scaling, Model selection, the top 5 most important variables are:

- OverallQual_Excellent: the overall material and finish of the house is excellent will indicate a higher price of the house
- GrLivArea: The area of living above ground (by square fit) is bigger, the higher the price of the house
- TotalBsmtSF:The area of basement (by square fit) is bigger, the higher the price of the house
- BsmtFinSF1: The area of Type 1 basement that is finished, the larger the area the higher the price
- GarageCars: The more cars the garage could accommodate, the higher the price

In general, the bigger and better the house is, the higher the price as both area and quality of various parts of the house are the most important variables.


