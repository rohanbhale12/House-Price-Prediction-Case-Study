# House Price Prediction Case Study
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

>The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

>The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.


>Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

-A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

-The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

-The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.


-Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Suggestions for Surprise Housing is to keep a check on these predictors affecting the price of the house.
The higher values of positive coeeficients suggest a high sale value.
1. GrLivArea - Above grade (ground) living area square feet
2. OverallQual - Rates the overall material and finish of the house
3. OverallCond - Rates the overall condition of the house
4. TotalBsmtSF - Total square feet of basement area
5. GarageArea - Size of garage in square feet
The higher values of negative coeeficients suggest a decrease in sale value.
1. PropertyAgeinYears - Age of the property at the time of the sale
2. MSSubClass - Identifies the type of dwelling involved in the sale

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
-numpy
-pandas
-matplotlib.pyplot
-seaborn
-sklearn - linear_model
-sklearn - linear_model - LinearRegression
-sklearn - linear_model - Ridge
-sklearn - linear_model - Lasso
-sklearn - model_selection - GridSearchCV
 - sklearn.preprocessing - PolynomialFeatures
-sklearn.linear_model - LinearRegression
-sklearn.pipeline - Pipeline
-sklearn - metrics
- os


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->