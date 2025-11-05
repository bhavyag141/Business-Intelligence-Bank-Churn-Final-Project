# Business Intelligence Final Project: Bank Churn Prediction
**Team Members:**

Bhavya Gutha, Kashika Singh, Sarwat Rattani, Roxane Makolo, Bhuvaneswari Kamireddi


**Context**

We have chosen the Bank Customer Churn Prediction dataset from Kaggle, and it contains information on bank customers who either left or continue to be a customer. As the name indicates, the banking industry is most relevant to our dataset, with the major stakeholders being the banks and the customers. Using this dataset, we plan to investigate the following questions:
- What are the attributes of the customers who are more likely to leave the bank?
- Can we develop customer classifications and allocate a propensity to churn score? 
These questions are useful to answer as they can help in building a predictive model that identifies customers who are likely to churn, thus allowing banks to come up with retention methods to keep their customers. This directly impacts banks bottom line that is their profitability and customer satisfaction score.


**Data and Variables**

Our dataset contains 13 variables and has 10,000 observations on banks’ customers. The dataset contains features of the customers such as credit score, tenure, balance, number of bank products  being utilized, credit card usage, and salary, which will help in predicting the target variable. Our target variable is whether a customer stayed with the bank or “Exited” - a binary outcome variable of interest. The dataset is large enough to conduct training and testing in order to validate the model. Missing values, depending on the type of variable, will be handled by either substituting the average value or leaving it blank (as in the case for binary variables).  We are also interested in exploring if we can utilize k-means clustering to identify customer groups and compare it with classification models to see how they both compare. 


**Following are our variables:** 

- Customer ID: A unique identifier for each customer
- Surname: The customer's surname or last name
- Credit Score: A numerical value representing the customer's credit score
- Geography: The country where the customer resides (France, Spain or Germany)
- Gender: The customer's gender (Male or Female)
- Age: The customer's age.
- Tenure: The number of years the customer has been with the bank
- Balance: The customer's account balance
- NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card)
- HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)
- IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)
- EstimatedSalary: The estimated salary of the customer
- Exited: Whether the customer has churned (1 = yes, 0 = no)
