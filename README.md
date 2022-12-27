# Advanced Regression

## Problem Statement - Part I
This assignment contains two parts. Part-1 is a programming assignment (to be submitted in a Jupyter notebook) whereas part-2 includes subjective questions (to be submitted in a PDF file). 

## Assignment Part-I
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual value and flip them at a higher price. For the same purpose, the company has collected a data set from house sales in Australia. The data is provided in the csv file below.

 

The company is looking at prospective properties to buy to enter the market.

You are required to build a regression model using regularization, so as to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

The company wants to know:

  - Which variables are significant in predicting the price of a house

  - How well those variables describe the price of a house

 

Also, determine the optimal value of lambda for ridge and lasso regression.

 

## Business Goal 

 
You are required to model the price of houses with the available independent variables. It will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high rewards. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Problem Statement - Part II

The following questions are the second part of the graded assignment.
 

Please limit your answers to less than 500 words per question.
 

 

**Question 1**

What is the optimal value of alpha for ridge and lasso regression? What will be the changes in the model if you choose double the value of alpha for both ridge and lasso? What will be the most important predictor variables after the change is implemented?

 

**Question 3**

You have determined the optimal value of lambda for ridge and lasso regression during the assignment. Now, which one will you choose to apply and why?

 

**Question 3**

After building the model, you realised that the five most important predictor variables in the lasso model are not available in the incoming data. You will now have to create another model excluding the five most important predictor variables. Which are the five most important predictor variables now?

 

**Question 4**

How can you make sure that a model is robust and generalisable? What are the implications of the same for the accuracy of the model and why?


## Technologies Used
- numpy - version 1.21.6
- pandas - version 1.3.0
- matplotlib - version 3.4.2
- seaborn - version 0.11.1
- statsmodels - version 0.12.2
- sklearn - version 0.24.2
 
## Conclusion
 
### Top 10 Best Performing Feature according to Lasso Regression are:

Lasso Regression performing best on given data with Test R2 Score of 92%

 |  Feature  |  Description  |
 |  ---  |  ---  |
 |  GrLivArea  |  Above grade (ground) living area square feet  |
 |  TotalBsmtSF  |  Total square feet of basement area 
 |  OverallQual  |  Rates the overall material and finish of the house  |
 |  Neighborhood |  Physical locations within Ames city limits|
 |  OverallCond  |  Rates the overall condition of the house  |
 |  house_age    |  Rates the overall condition of the house|
 |  BsmtFinSF1   |  Type 1 finished square feet|
 |  LotArea      |  Lot size in square feet|
 |  ExterQual    |  Evaluates the quality of the material on the exterior |
 |  SaleType     |  Type of sale|
 
