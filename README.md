# Credit Card Churn Prediction for Thera Bank

## Objective
Thera Bank has recently experienced a significant decline in the number of credit card users. Credit cards are a crucial source of income for the bank, generating various fees like annual fees, balance transfer fees, late payment fees, and others.  

Customers’ leaving credit card services would lead the bank to loss, so the bank wants to analyze the data of customers and identify the customers who will leave their credit card services and the reason for same – so that the bank could improve upon those areas.

The bank wants to:
1. Analyze customer data to identify patterns and reasons for customer churn.
2. Build a classification model to predict customers likely to leave.
3. Provide actionable insights and recommendations to improve customer retention.

---

## Dataset Description
The dataset contains the following features:

| **Feature**                   | **Description**                                                                                 |
|-------------------------------|-------------------------------------------------------------------------------------------------|
| `CLIENTNUM`                   | Unique identifier for the customer holding the account.                                        |
| `Attrition_Flag`              | Internal event variable: `"Attrited Customer"` if the account is closed, otherwise `"Existing Customer"`. |
| `Customer_Age`                | Age of the customer (in years).                                                                |
| `Gender`                      | Gender of the account holder.                                                                  |
| `Dependent_count`             | Number of dependents.                                                                          |
| `Education_Level`             | Educational qualification (e.g., Graduate, High School, College, Post-Graduate, Doctorate).   |
| `Marital_Status`              | Marital status of the account holder.                                                         |
| `Income_Category`             | Annual income category of the account holder.                                                 |
| `Card_Category`               | Type of credit card issued.                                                                   |
| `Months_on_book`              | Duration of the relationship with the bank (in months).                                        |
| `Total_Relationship_Count`    | Total number of products held by the customer.                                                |
| `Months_Inactive_12_mon`      | Number of months the customer was inactive in the last 12 months.                              |
| `Contacts_Count_12_mon`       | Number of contacts between the customer and the bank in the last 12 months.                   |
| `Credit_Limit`                | Credit limit on the credit card.                                                              |
| `Total_Revolving_Bal`         | Revolving balance carried over from one month to the next.                                    |
| `Avg_Open_To_Buy`             | Average amount available for purchases over the last 12 months.                               |
| `Total_Trans_Amt`             | Total transaction amount in the last 12 months.                                               |
| `Total_Trans_Ct`              | Total transaction count in the last 12 months.                                                |
| `Total_Ct_Chng_Q4_Q1`         | Ratio of total transaction count in Q4 to Q1.                                                 |
| `Total_Amt_Chng_Q4_Q1`        | Ratio of total transaction amount in Q4 to Q1.                                                |
| `Avg_Utilization_Ratio`       | Proportion of available credit used by the customer.                                          |

---
