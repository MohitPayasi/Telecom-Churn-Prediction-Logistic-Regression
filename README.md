# Telecom-Churn-Prediction-Logistic-Regression
![image](https://user-images.githubusercontent.com/100429769/206727326-97575674-a808-453f-ba4b-ad2d813fb048.png)

For Telecom companies it is key to attract new customers and at the same time avoid contract terminations (=churn) to grow their revenue generating base. Looking at churn, different reasons trigger customers to terminate their contracts, for example better price offers, more interesting packages, bad service experiences or change of customers’ personal situations.

Churn analytics provides valuable capabilities to predict customer churn and also define the underlying reasons that drive it. The churn metric is mostly shown as the percentage of customers that cancel a product or service within a given period (mostly months).

## Problem Statement

A Telecom company is losing Customers to its competitors. With the historical customer churn information that they have, they want a ML Model to predict, which of their present customers may churn.We have decided to create a Logistic Regression model to solve the problem. The Logistic Regression model will be expected to output a Churn Probability for every data under test.

## Dataset

The input data is spread over 3 separate files - churn_data.csv, cust_data.csv and internet_data.csv.

The Data includes the following:

   -Personal Data (gender, children, whether senior citizen, dependents...)
     
   -Services Related (Tenure with the provider, payment method, internet packs purchased, special offers...)

   -Charges being incurred (Amount of recharge done per month...)
   
## Optimisation 

We optimized our model using Statsmodel Logit(), we will create a corresponding model using ScikitLearn LogisticRegression()
Some Differences between Logit and LogisticRegression

    -ScikitLearn LogisticRegression: Uses L2 regularization by default, but regularization can be turned off using penalty=’none’. StatsModel Logit: Does not use            regularization by default.
    
    -ScikitLearn LogisticRegression: Includes intercept by default. StatsModel Logit: Use the add_constant method to include an intercept.   
   
## Conclusions

