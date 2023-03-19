# Loan Eligibility Prediction

A Company wants to automate the loan eligibility process based on customer details provided while filling online application form. The details filled by the customer are Gender, Marital Status, Education, Number of Dependents, Income of self and co applicant, Required Loan Amount, Required Loan Term, Credit History, and others.

## About the features

```text
Loan_ID --> Unique id for every loan request
Gender --> Applicant's Gender
Married --> Applicant's Marital status
Dependents --> How many people are dependent on the Applicant in his/her family.
Education --> Applicant's Education
Self_Employed --> Whether the applicant is employed | Owner of business
ApplicantIncome --> Applicant's Income on record
CoapplicantIncome --> CoApplicant's Income on record
LoanAmount --> Amount of Loan required
Loan_Amount_Term --> Duration in which applicant wants to pay back the loan amount.
Credit_History --> Whether the candidate has good or bad credit history in past
Property_Area --> Type of locality of property which the candidate has given as mortgage. The type tells us about property valuation.
```

## Files

```text
1_preprocessing.ipynb
    - handles missing/null values 
    - handles outliers
    - encoding object type features
    - normalizing numerical features
    - data visualization
    - handles class imbalance
2_model_training.ipynb
    - feature selection
    - splitting data into train and test
    - training models
        * Logistic Regression
        * Random Forest Classifier
        * Gradient Boosting Classifier
        * Support Vector Machines
        * Artificial Neural Networks
3_model_evaluation.ipynb
    - accuracy score
    - confusion matrix
    - AUC-ROC curve
```
