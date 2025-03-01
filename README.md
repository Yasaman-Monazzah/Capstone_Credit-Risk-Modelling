# Capstone_Credit-Risk-Modelling

##  Project Overview
This project aims to develop a predictive model for loan default risk by leveraging a comprehensive dataset that includes loan characteristics, borrower demographics, and credit history information.

## Problem Statement and Proposed Solution
Loan defaults have profound implications for financial institutions and the broader economy. The 2008 financial crisis, which was largely driven by widespread defaults on subprime loans, demonstrated the devastating impact that poorly managed credit risk can have on the entire financial system. This project seeks to improve risk management by accurately predicting loan defaults, thereby helping lenders make more informed decisions, optimize their portfolios, and reduce financial losses. 
In Sprint 2, I will begin by constructing a baseline logistic regression model using scikit-learn. I will also explore additional models such as Support Vector Machines, Decision Trees, Random Forests, and XGBoost.


## Dataset Description
The dataset used for analysis is obtained from Kaggle: [https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter](https://www.kaggle.com/datasets/jeandedieunyandwi/lending-club-dataset)

Dataset includes a wide range of features, including:

Loan Characteristics:

- loan_amnt: The total loan amount in dollars.

- term: Loan duration (e.g., "36 months" or "60 months").

- int_rate: The interest rate applied to the loan.

- installment: The monthly repayment amount.



Borrower Demographics and Credit History:

- grade and sub_grade: Credit risk ratings assigned to the loan.

- emp_length and emp_length_numeric: Employment length, presented in categorical form and converted to a numeric value.

- home_ownership: Borrower’s housing status (e.g., RENT, MORTGAGE, OWN).

- annual_inc: Annual income.

- verification_status: Whether the borrower’s income was verified.

- earliest_cr_line: Date of first credit establishment, used to derive credit age.

- open_acc, pub_rec, revol_bal, revol_util, total_acc, mort_acc, and pub_rec_bankruptcies: Various indicators of credit behavior and history.


Other Relevant Features:


- issue_d: The date when the loan was issued.

- loan_status: The outcome of the loan, our target variable (Default or Fully Paid).

- purpose, title, dti, initial_list_status, application_type, and address: Additional information that provides context for each loan.


## Impact of Solution
Accurate prediction of loan default risk can have a transformative impact on the financial industry. By accurately predicting loan defaults, the model will help bank and financial institutions improve risk management, optimize loan offerings, and minimize losses. Additionally, it can promote fairness in lending practices, ensuring that those who can repay are approved for loans while protecting against those who may struggle.
