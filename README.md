# Loan Approval Prediction Model

A server side machine learning Model that can predict the approval of an Loan Applicant with some general data.

# Description #

 * Given the loan dataset. The objective is to determine the eligibility of the said applicant for the loan.
 * The Dataset contains data like LoanAmount, Education, Dependents, CreditHistory, Income, etc.
 * The target variable is Loan_Status.

# My Procedure #

## Cleaning
* The dataset has inconsistent empty values. To tackle that, a simple panda replace would do the trick.
* Substituting an estimated value for missing values in a dataset with the help of mean,mode,median.
* Removing Outliers and Infinite Values

## Data Preprocessing
* Distribution for ApplicantIncome, CoapplicantIncome, and LoanAmount is positively skewed, used 'Sqaure Root Transformation' to normalize the distribution.
* Used SMOTE Technique is used to counter the overfitting of the model.
* Data normalization is performed to normalize the range of independent variables or features of data.

## Model Training
* Logistic Regression, Random Forest, Gradient Boosting, KNN, SVC, Naive Bayes, Decision Tree, XGBoost were used.
* All the models were implemented and compared to choose the best accuracy possible for the prediction.
* In general, it can be seen that all models can achieve up to 70% accuracy.
  The highest accuracy is 93%%.
