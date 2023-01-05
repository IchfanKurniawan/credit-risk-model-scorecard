# Loan Credit Risk Model  
Build a predictive model to understand factors that influence the credit default  


**Status**: Done  
**Jupyter notebook**: here  
This project is rework from my previous project here.

---
---

## Summary   

1. Loan credit risk model is built using maching learning model Logistic Regression.  
2. The final model performances are as follow:
    - **AUCROC**: 0.9224
    - **Gini**: 0.8449
    - **Kolmogorov-Smirnov**: 0.8534
3. The final model is turned into scored card for ease of operation in frontdesk & exported as csv (elaborated in modeling phase notebook)
4. Based on the model & scorecard:
    - with the 95% threshold (probability of not default), we shall reject customers with score lower than 672 & we will get 11.36% approval rate  
    - with the 90% threshold (probability of not default), we shall reject customers with score lower than 664 & we will get 14,19% approval rate  
    - with the 85% threshold (probability of not default), we shall reject customers with score lower than 659 & we will get 17,13% approval rate  
  
---  
---  
## <span id='all'>All about Projects</span>  
    
#### Project Context  
From the prespective of financial institution like a bank, finding a good borrower is a must to run their financing businesses. Not only make a bad impact to the business, bad borrowers could also give a negative impact to a broader economic.  
This project will elaborate any factor that affects the credit default and builds a model to predict it.


#### Project Requirement   

1. Explore and prepare the dataset  
2. Train a machine learning model to predict the credit default from borrower.
3. Evaluate model based on metrics (AUCROC, Gini, Kolmogorov-Smirnov)  
4. Final outcome: Scorecard & Machine Learning model

#### Project Planning  
1. Exploratory Data Analysis (EDA)
    - Data Structure Check (shape, datatype, head, tail)
    - Data Quality Check (missing value, outlier, distribution)
    - Data Cleaning (missing value, outlier, inappropiate values, high cardinality)
    - Content Investigation (hypothesis testing, predictive power check through descriptive/visualization and analytics)
2. Data Preporcessing & Feature Engineering
3. Feature Selection
4. Models Training
5. Models Evaluation  
