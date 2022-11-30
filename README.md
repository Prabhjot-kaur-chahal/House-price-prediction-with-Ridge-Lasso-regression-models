# House-price-prediction-with-Ridge-Lasso-regression-models
# House_Price_Prediction_Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

* <a href="https://github.com/Prabhjot-kaur-chahal/House-price-prediction-with-Ridge-Lasso-regression-models/blob/main/train.csv">Dataset</a>

> The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [Business Goal](#business-goal)
* [Technologies Used](#technologies-used)
* [Code](#code)
* [Conclusions](#conclusions)
* [Contact](#contact)


## Business Goal
Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
Determine the optimal value of lambda for ridge and lasso regression.
This model will then be used by the management to understand how exactly the prices vary with the variables
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
The model will be a good way for the management to understand the pricing dynamics of a new market.



## Technologies Used
- Scikit-Learn
- Matplotlib
- Numpy
- Seaborn
- Pandas

## Conclusions
* The optimum lambda value in case of Ridge and Lasso is as follows:-

> Ridge – 2
  Lasso – 0.0001
* The Mean Squared Error in case of Ridge and Lasso are:

> Ridge - 0.0018396090787924262
  Lasso - 0.0018634152629407766

* The Mean Squared Error of both the models is almost same.

* Since Lasso helps in feature reduction (as the coefficient value of some of the features become zero), Lasso  has a better edge over Ridge and should be used as the final model. 

## Contact
Created by [@Prabhjot-kaur-chahal](https://github.com/Prabhjot-kaur-chahal)
