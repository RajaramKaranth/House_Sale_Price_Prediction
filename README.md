# House Price Prediction Assignment
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia to assess.
The company is looking at prospective properties to buy to enter the market. The assignment is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.

and also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This project is to assist a US-based housing company named SurpriseHousing with a regression model using regularization in order to predict the the actual value of the prospective properties in Australia that will help them decide whether to invest in them or not.

The model is supposed to price the houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia to assess. This dataset is used in this assignment to build models using regularization. 

In this assignment 
- Data understanding and exploration is done in detail. AutoEDA is used to help with understanding the large number of features using sweetviz package. 
- Data cleaning is performed by handling the null values which are meant to be one of the valid values of the feature and not null. 
- Data preparation involved changing the SalePrice to logarithmic scale to make it normally distributed. Categorical strings are changed to numerical values.
- Both Lasso and Ridge regression models have been built for different lambda values to identify the optimal value of lambda.
- Experimentations required to answer the subjective questions are also part of this assignment solution.


## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis
- Few variables are shown to be having high numberof null values. However they were indicating one of the valid values of the feature and not null.
- The skew for SalePrice is >1 that indicates the data we have is highly skewed. The Kurtosis for SalePrice is >6, indicates the distribution is tall and the data has more outliers.
- During the analysis, it appears that the target, SalePrice, is very skewed and a transformation like a logarithm would make it more normally distributed such that model can perform better w-ith normally distributed targets. 
- Lasso regression for lambda values between 0 and 1.5 indicated a huge gap between the R2 values at alpha values between 0 and 0.2. They have reasonably good R2 at alpha value around 0.5 and 0.6.
- The lambda values considered for Lasso didn't provide good r2 scores when Ridge regression was applied. Experimented with higher lambda values.
- alpha value around 9 in Ridge regression showed very good r2 scores.


## Technologies Used
- Python - version 3.10.9
- pandas - version 1.5.3
- numpy - version 1.23.5
- seaborn - version 0.12.2
- jupyter notebook - version 6.5.2
- sweetviz - version 2.2.1
- scikit-learn - version 1.2.1
- scipy - version 1.10.0
- matplotlib - version 3.7.0 


## Acknowledgements
Give credit here.
- This assignment is based on the learnings from Advanced Regression module of ML C54 EPGP program by IIIT Bangalore and upGrad.
- The live session from Syan Dey and the instructor videos in the module by Anjali Rajvanshi has immensely helped in understanding the Regularization concepts and applying in this assignment. 


## Contact
Created by https://github.com/RajaramKaranth 
