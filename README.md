# Advanced-Regression
Australia Housing Price Prediction using Advanced Regression (Lasso and Ridge techniques)

<b>Business Goal</b>:
 Build the model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
Steps we will follow in this assignment as follow:
1. Reading, understanding and visualising the data
    - importing python libraries
    - load the data
    - checking the data type of each features
    - checking null and percentag of null values in each features
    - visualize the data for better understanding
2. Preparing the data for modelling(train-test split etc)
    - remove the outliers
    - impute missing values with mean etc
    - verifying the correlation to target saleprice variable
    - drop feature which are not useful for prediction of saleprice
    - split data as train and test 
3. Model building and evaluation
    - building model with Linear regression with help of RFE
    - Lasso and Ridge Regression
        - Ridge Regression
        - Lasso Regression
4. Observation
