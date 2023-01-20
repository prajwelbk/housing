# House Price Prediction
> Predicting housing prices based on regulaized regression models such as lasso and ridge.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
- The company is looking at prospective properties to buy to enter the market. A regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not has to be build.
- The company wants to know:
  - Which variables are significant in predicting the price of a house?
  - How well those variables describe the price of a house?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Obtained regularized model using Lasso & Ridge regressions.
- On Unseen data we got the following accuracy:
  - Ridge : 89.9
  - Lasso : 91.3
- Top Predictors of Ridge
  - 'GrLivArea','OverallQual','TotalBsmtSF','BsmtFinSF1','Neighborhood_StoneBr'
- Top Predictors of Lasso
  - 'GrLivArea','OverallQual','TotalBsmtSF','OverallCond','Neighborhood_StoneBr'



## Technologies Used
- numpy
- pandas
- seaborn
- matplotlib
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project is done as part of Execution PG on ML & AI from upgrade with partnership with IIITB
- This project was based on [this tutorial](https://github.com/ContentUpgrad/Advanced-Regression).


## Contact
Created by [@prajwelbk] - feel free to contact me!
