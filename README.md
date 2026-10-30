# Bank Customer Churn Prediction

Binary classification model predicting bank customer churn to support targeted retention strategies.

## Objective

The goal of this project is to predict whether a customer will keep using the bank's services or close their account (churn). The dataset contains demographic, financial and behavioral features for each customer. The model predicts, for every customer, whether they are likely to leave, enabling the bank to design effective retention strategies.

## Data

The data comes from a private Kaggle competition of the ML-PRO training program (`mlpro-classification-bank-churn-2025`) and is not versioned in this repository.

The features are:

- **CustomerId**: unique customer identifier
- **Surname**: customer's surname
- **CreditScore**: numerical value representing the customer's credit score
- **Geography**: country of residence (France, Spain or Germany)
- **Gender**: customer's gender (Male or Female)
- **Age**: customer's age
- **Tenure**: number of years the customer has been with the bank
- **Balance**: account balance
- **NumOfProducts**: number of bank products held (e.g. savings account, credit card)
- **HasCrCard**: whether the customer has a credit card (1 = yes, 0 = no)
- **IsActiveMember**: whether the customer is an active member (1 = yes, 0 = no)
- **EstimatedSalary**: customer's estimated salary
- **Exited**: target variable, whether the customer churned (1 = yes, 0 = no)