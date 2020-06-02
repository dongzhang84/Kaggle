# Home Credit Default Risk

This is for the Kaggle Project [here](https://www.kaggle.com/c/home-credit-default-risk)

[Home Credit Task 1](https://github.com/dongzhang84/Kaggle/blob/master/Home%20Credit%20Default%20Risk/Home_Credit_1.ipynb): Load **application_train.csv** and **application_test.csv**, check missing data, encode categorical data, correlation, deploy baseline models (Logistic Regression, Random Forest, XGBoost). 

[Home Credit Task 2](https://github.com/dongzhang84/Kaggle/blob/master/Home%20Credit%20Default%20Risk/Home_Credit_2.ipynb): merge previous_loan_counts from bureau.csv to original df_train, df_test, 'count', 'mean', 'max', 'min', 'sum' for numerical fields, 'mean', 'sum' for categorical fields, remove Collinear Variables, lightgbm k-Fold

[Home Credit Task 3](https://github.com/dongzhang84/Kaggle/blob/master/Home%20Credit%20Default%20Risk/Home_Credit_3.ipynb): Basically same as [Home Credit Task 2](https://github.com/dongzhang84/Kaggle/blob/master/Home%20Credit%20Default%20Risk/Home_Credit_2.ipynb), make LightGBM K-fold as a function. Test XGBoost, feature importance discussion. 

[Home Credit Task 4](https://github.com/dongzhang84/Kaggle/blob/master/Home%20Credit%20Default%20Risk/Home_Credit_4.ipynb): load **previous_application.csv**, **POS_CASH_balance.csv**, **credit_card_balance.csv**, **installments_payments.csv** for feature engineering and LightGBM modeling. Also add previous fields from Home Credit Task 2 and 3.


[Home Credit Task 5](https://github.com/dongzhang84/Kaggle/blob/master/Home%20Credit%20Default%20Risk/Home_Credit_5.ipynb): Automated Feature Engineering Basics (Featuretools).

