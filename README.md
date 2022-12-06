# Project Name
> In this Surprise Housing assignment I am trying to build a Lasso & Ridge Regression model for the prediction of Housing Price. This assignment is to learn how to apply the Lasso & Ridge Regression concept of Machine Learning to find out important prediction variables and reduction of coefficient magnitude.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- BACKGROUND : A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

    The company is looking at prospective properties to buy to enter the market. Requirement is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

    The company wants to know:
        
        Which variables are significant in predicting the price of a house?

        How well those variables describe the price of a house?

 

    Also, determinining the optimal value of lambda for ridge and lasso regression.

- PROBLEM STATEMENT : Requirement is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- DATASET USED : The given dataset used "train.csv" for the assignment contains information about different factors that affect the price of the house i.e. the set of independent variables and dependent variable.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The most important predictor variables are:

1.	OverallQual_9
2.	GrLivArea
3.	OverallQual_8
4.	OverallCond_9
5.	Neighborhood_Crawfor
6.	Exterior1st_BrkFace

- A model is robust when any variation in the data does not affect its performance much and a generalizable model is able to adapt properly to new, previously unseen data, drawn from the same distribution as the one used to create the model.

- To make sure a model is robust and generalizable, we have to take care it doesn't overfit. This is because an overfitting model has very high variance and a smallest change in data affects the model prediction heavily. Such a model will identify all the patterns of a training data, but fail to pick up the patterns in unseen test data. In other words, the model should not be too complex in order to be robust and generalizable.

- In general, we have to find some balance between model accuracy and complexity. This can be achieved by Regularization techniques like Ridge Regression and Lasso.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python language is used for coding and Jupyter Notebook is used for that. Libraries used in python: pandas, numpy, matplotlib.pyplot, seaborn, sklearn, statsmodels.
For collaboration, I have used Github platform.


## Acknowledgements
This assignment was done as part of the UpGrad course.


## Contact
Created by @DhanshreeVyas - feel free to contact me!