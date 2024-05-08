# credit-risk-classification

## Overview of the Analysis

* The purpose of the activity is to be able to check someone's availability to obtain a loan. This is based on the lending_data.csv file provided with loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt and loan_status per person which help us indicate if the borrower is a high risk or low risk loaner. 

* The two variables are 1 and 0. When a borrower is determined to be "0", it indicates that the loan risk is low and based on the information provided of this person, this is a healthy loan and when the borrower is determined to be a "1", this indicates this is a high risk loan. 

* The stages of the machine learning process used for this analysis were the following: Split the data into testing and training sets, create the label "y" and create dataframe "x", split the data into training and testing datasets, create a logistic regression model making a prediction with a fit model.

* Some of the methods used on the activity are: RandomOverSampler from imbalanced-learn to resample the data. Split the data into training and testing datasets by using `train_test_split`. Fit a logistic regression model by using the training data (`X_train` and `y_train`) and LogisticRegression to determine each person as a low or high risk as the only two variables. 

## Results
* Machine Learning Model 1:
    * Accuracy is 99% in this model.
    * Precision is 100% for low risk loans and 85% for high risk loans.
    * Recall is 99% accurate for low risk vs 91% for high risk. This show us the percentage of times the loan was classified correctly.

## Summary

Based on the results above, we can say the healthy loans perform best with an overall of 100-99% accuracy. The data provided has a significantly bigger amount of borrower classified as low risk and that might affect the outcome of the activity. 

The activity was to determine if the borrower is creditworthiness so there is only option high risk and low. Even high risk does not has as good accuracy as low risk, overall this is a good toll to determine whether the borrower should receive a loan or not. 

