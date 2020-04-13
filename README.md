# Churn-Prediction

Churn prediction is common use case in machine learning domain. If you are not familiar with the term, churn means "leaving the company". It is very critical for business to have an idea about why and when customers are likely to churn. Having a robust and accurate churn prediction model helps businesses to take actions to prevent customers from leaving the company.

In this project, I will use "Telco Customer Churn" data set which is available on Kaggle.

There are 20 featuures (independent variables) and 1 target (dependent) variable for 7043 customers. Target variable indicates if a customer has has left the company (i.e. churn=yes) within the last month. Since the target variable has two states (yes/no or 1/0), this is a binary classification problem.

The variables are: 
customerID: Customer ID 
gender: Gender of customer 
SeniorCitizen: Whether the customer is a senior citizen or not (1, 0) 
Partner: Whether the customer has a partner or not (Yes, No) 
Dependents: Whether the customer has dependents or not (Yes, No) 
tenure: Number of months the customer has stayed with the company 
PhoneService: Whether the customer has a phone service or not (Yes, No) 
MultipleLines: Whether the customer has multiple lines or not (Yes, No, No phone service) 
InternetService: Customer’s internet service provider (DSL, Fiber optic, No) 
OnlineSecurity: Whether the customer has online security or not (Yes, No, No internet service) 
OnlineBackup: Whether the customer has online backup or not (Yes, No, No internet service) 
DeviceProtection: Whether the customer has device protection or not (Yes, No, No internet service) 
TechSupport: Whether the customer has tech support or not (Yes, No, No internet service) S
treamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service) 
StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No internet service) 
Contract: The contract term of the customer (Month-to-month, One year, Two year) 
PaperlessBilling: Whether the customer has paperless billing or not (Yes, No) 
PaymentMethod: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)) 
MonthlyCharges: The amount charged to the customer monthly TotalCharges: The total amount charged to the customer 
Churn: Whether the customer churned or not (Yes or No)
