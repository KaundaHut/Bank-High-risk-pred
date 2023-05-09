# Bank-High-risk-pred

## Problem Statement 

 Predicting high-risk customers who are likely to churn for the banking industry

 A  bank is struggling to maintain its strong foothold in the local market due to: 

     * Rapidly increasing customer churn which leads to revenue loss for the bank
    
     * The decline in overall customer base (high churn rate combined with low acquisition rate), leading to a decline in total market share. 
     
     * Bank want to retain customer to stop revenue loss
     

#### Data Source : Kaggle

## Data Description :

 * RowNumber : Row number
 
 * CustomerId : Unique Customer ID
  
 * Surname: Last Name of the Customer
 
 * CreditScore: Credit score of the customer
 
 * Geography:  Country of the customer
 
 * Gender: Gender of the customer
 
 * Age: Current age of the customer
 
 * Tenure: No. Of years customer with the bank
 
 * Balance: Account balance of the customers
 
 * NumOfProduct: Number of the products used by customer with the bank
 
 * HasCrCard: Customer owns credit card or not
 
 * isActiveMember: Customer is active member ( Interaction with App/Web Bank Application)
 
 * Estimated Salary: Salary of the customers
 
 * Exited: Yes if customer churned else no

## Contents :

 * Loading of dataset, libraries and basic statistics of the data
 
 * EDA 
 
 * Data Preprocessing  
 
     * Removal of columns
     
     * Encoding of Categorical Varibales
     
 * Predictive Modeling 
 
   * Testing different balancing techniques (on Logistic Regression)
   
   * Function to evaluate classifier (Reduce code size and increase reusability of the code)
   
   * Random Forest 
   
   * Hyperparameter tunning of Random Forest
   
   * Boosting model comparision  : XGBoost,CatBoost, LightGBM
   
   * Hyperparameter tunning of Boosting model
   
   * Hyperparameter tunning of boosting models
   
   * Model interpretability using SHAP (SHapley Additive exPlanations)
   
   * Understanding model prediction
   
   * Sample prediction from model
   
   * Efficient probablity Threshold Cut-off for better recall


