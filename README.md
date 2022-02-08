# House Price Prediction
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.

The company wants to know:

- Which variables are significant in predicting the price of a house

- How well those variables describe the price of a house.
### Business Goal
- The company is looking at prospective properties to buy to enter the market.
- Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- Determine the optimal value of lambda for ridge and lasso regression.
- Model the price of houses with the available independent variables.
- This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and         concentrate on areas that will yield high returns.
- The model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Reading and Understanding the Data
- Basic Data Cleanup
- Missing value check and imputation using Business Logic.
- Changing data types of the variables.
- Performed Univariate and Bi-variate analysis on identified variables and Correlation heatmap.
- Data Preparation for model building.
- Performed log transformation of target variable.
- Encoding categorical features
- Performed Scaling of numerical features using median and quantile values.
- Performed Variance Thresholding to exclude the features having almost zero variance.
- Ridge Regression model with GridSearchCV to find optimal value of alpha.
- Identified top 15 features based on beta coefficient values.
- Lasso Regression model with GridSearchCV to find optimal value of alpha.
- Identified top 15 features based on beta coefficient values.
- Evaluate both the model on training and test dataset.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Ridge and Lasso both the models have almost same test and train accuracy, there is no overfitting.
- Number of features in Lasso Regression model is 104. Where Ridge has all 216 features.
- Lasso model is simpler than Ridge with having similar r2 score and MAE.
- Ridge Regression model on test dataset: r2 score= 0.8900, MAE= 0.0940, RMSE= 0.1364
- Lasso Regression model on test dataset: r2 score= 0.8949, MAE= 0.0915, RMSE= 0.1333
- Considering above points we can choose Lasso Regression model as final model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Language : Python 3.8.8

Notebook : Jupyter notebook 6.3.0

Library : Numpy, Pandas, matplotlib, sklearn and seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.


## Contact
Created by [@KrishnamoorthyVK] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
