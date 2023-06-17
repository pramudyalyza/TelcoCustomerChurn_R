# TelcoCustomerChurn_R
This project focuses on creating a model to predict customer churn in Telco, which helps us identify customers who are likely to leave the company. By predicting customer churn, we can take proactive measures to retain customers and prevent them from leaving. Retaining existing customers is crucial for business growth and success, as it is generally more cost-effective than acquiring new customers.

**Files**<br>
* Soal 2 - Telco Customer Churn.Rmd: An R Markdown file containing the code, analysis, visualizations for exploring the dataset and a predictive models in R.
* Soal 2 - Telco Customer Churn.pdf: A pdf file contains explanation for each line of code in R Markdown

**Dataset**<br>
The dataset used in this analysis is sourced from Kaggle and can be accessed at the following link: [Telco Customer Churn](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)). Please download the dataset from the provided link before running the code.

**Column Description**<br>
The dataset used for this project contains information about Telco customers' demographic characteristics and account details. It includes the following columns:
* **CustomerID:** Unique customer identifier.
* gender: Gender of the customer (Male or Female).
* SeniorCitizen: Whether the customer is a senior citizen (1 or 0).
* Partner: Whether the customer has a partner (Yes or No).
* Dependents: Whether the customer has dependents (Yes or No).
* tenure: Number of months the customer has stayed with the company.
* PhoneService: Whether the customer has a phone service (Yes or No).
* MultipleLines: Whether the customer has multiple lines (Yes, No, or No phone service).
* InternetService: Customer's internet service provider (DSL, Fiber optic, or No).
* OnlineSecurity: Whether the customer has online security (Yes, No, or No internet service).
* OnlineBackup: Whether the customer has online backup (Yes, No, or No internet service).
* DeviceProtection: Whether the customer has device protection (Yes, No, or No internet service).
* TechSupport: Whether the customer has tech support (Yes, No, or No internet service).
* StreamingTV: Whether the customer has streaming TV (Yes, No, or No internet service).
* StreamingMovies: Whether the customer has streaming movies (Yes, No, or No internet service).
* Contract: The contract term of the customer (Month-to-month, One year, or Two year).
* PaperlessBilling: Whether the customer has paperless billing (Yes or No).
* PaymentMethod: The customer's payment method (Electronic check, Mailed check, Bank transfer (automatic), or Credit card (automatic)).
* MonthlyCharges: The amount charged to the customer monthly.
* TotalCharges: The total amount charged to the customer.
* Churn: Whether the customer churned (Yes or No).<br>

The goal of this project is to develop a predictive model that can accurately classify customers as churned or non-churned based on the provided features.


