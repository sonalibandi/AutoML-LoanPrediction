# AutoML-LoanPrediction

# AutoML Loan Prediction Analysis

## Abstract
This project aims to identify the variables that make the most sense in predicting loan statuses. We employ H2O AutoML to evaluate the model's accuracy and to understand feature importance, especially those with high multicollinearity.

## Data Set
The dataset comprises 12 attributes, primarily revolving around personal attributes and loan details. Our target variable, `loan_status`, indicates whether a client has repaid the loan amount (0) or has defaulted (1). The dataset contains 18,000 observations tracking this loan status.

## Research Questions

1. Which features are most predictive of the target variable? This aids in feature selection and interpretation of the model.
2. Are any model assumptions violated?
3. Is there multicollinearity in the model?
4. In multivariate models, which are the most significant predictor variables? How can we exclude insignificant ones from the model?
5. Does regularization improve the model's performance?
6. Which independent variables significantly influence the target variable?
7. Which hyperparameters play a crucial role in the model's performance?

## Tools Used
- H2O AutoML

## Contributors
- Sonali Bandi


