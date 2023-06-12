# Problem Description
A credit card company wants to find out why some of their customers end up opting out of their service. This can be solved by fitting a model that best categorized a customer as an existing customer or not and then plotting the feature importances to see what factors drive attrition. The [solution notebook](https://github.com/KevKibe/Credit-Card-Users-Churn-Prediction/blob/main/model_and_Inference.ipynb)

# Data Description
The [dataset](https://github.com/KevKibe/Credit-Card-Users-Churn-Prediction/blob/main/BankChurners%20(1).csv) provided has customer data and whether they are existing customers or they opted out(attrited customer).

# Findings
**Feature Importances**
  
![image](https://github.com/KevKibe/Credit-Card-Users-Churn-Prediction/assets/86055894/12baad8f-a4dc-47b8-b432-5031dd28bef5)

# Factors that drive attrition are :

- **Total_Trans_Ct:** Less number of transactions in a year leads to attrition of a customer - to increase the usage of cards the bank can provide offers like cashback, special discounts on the purchase of something, etc so that customers feel motivated to use their cards.
  
- **Total_Revolving_Bal:** Customers with less total revolving balance are the ones who attrited, such customers must have cleared their dues and opted out of the credit card service. After the customer has cleared the dues bank can ask for feedback on their experience and get to the cause of attrition.
  
- **Total_Trans_Amt:** Less number of transactions can lead to less transaction amount and eventually leads to customer attrition Bank can provide offers on the purchase of costlier items which in turn will benefit the customers and bank both.
  
- **Total_Relationship_Count:** Attrition is highest among the customers who are using 1 or 2 products offered by the bank together they constitute ~55% of the attrition - Bank should investigate here to find the problems customers are facing with these products. Customer support, or more transparency can help in retaining customers.
  
- Female customers should be the target customers for any kind of marketing campaign as they are the ones who utilize their credits, make more and higher amount transactions. But their credit limit is less, so increasing the credit limit for such customers can profit the bank.
  
- **Months_Inactive:** As inactivity increases the attrition also increases. 2-4 months of inactivity are the biggest contributors of attrition - Bank can send automated messages to engage customers, these messages can be about their monthly activity, new offers or services, etc.
  
- Highest attrition is among the customers who interacted/reached out the most with/to the bank, this indicates that the bank is not able to resolve the problems faced by customers leading to attrition - a feedback collection system can be set up to check if the customers are satisfied with the resolution provided, if not, the bank should act upon it accordingly.
