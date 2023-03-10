# Credit-Card-Users-Churn-Prediction
A predictive model to identify customers who are at risk of attrition in order to find the key causes that drive attrition. This can help banks  take appropriate actions to build better retention policies for customers.

# Data Description
<li>CLIENTNUM - Client number. Unique identifier for the customer holding the account
<li>Attrition_Flag - Internal event (customer activity) variable - if the account is closed then "Attrited Customer" else "Existing Customer"
<li>Customer_Age - Age in Years
<li>Gender - Gender of the account holder
<li>Dependent_count - Number of dependents
<li>Education_Level - Educational Qualification of the account holder - Graduate, High School, Unknown, Uneducated, <li>College(refers to college student), Post-Graduate, Doctorate
<li>Marital_Status - Marital Status of the account holder
<li>Income_Category - Annual Income Category of the account holder
<li>Card_Category - Type of Card
<li>Months_on_book - Period of relationship with the bank (in months)
<li>Total_Relationship_Count - Total no. of products held by the customer
<li>Months_Inactive_12_mon - No. of months inactive in the last 12 months
<li>Contacts_Count_12_mon - No. of Contacts in the last 12 months
<li>Credit_Limit - Credit Limit on the Credit Card
<li>Total_Revolving_Bal - Total Revolving Balance on the Credit Card
<li>Avg_Open_To_Buy - Open to Buy Credit Line (Average of last 12 months)
<li>Total_Amt_Chng_Q4_Q1 - Change in Transaction Amount (Q4 over Q1)
<li>Total_Trans_Amt - Total Transaction Amount (Last 12 months)
<li>Total_Trans_Ct - Total Transaction Count (Last 12 months)
<li>Total_Ct_Chng_Q4_Q1 - Change in Transaction Count (Q4 over Q1)
<li>Avg_Utilization_Ratio - Average Card Utilization Ratio


What is a Revolving Balance?<br>
If we don't pay the balance of the revolving credit account in full every month, the unpaid portion carries over to the next month. That's called a revolving balance.<br>

What is the Average Open to buy?<br>
'Open to Buy' means the amount left on your credit card to use. Now, this column represents the average of this value for the last 12 months.<br>

What is the Average utilization Ratio?<br>
The Avg_Utilization_Ratio represents how much of the available credit the customer spent. This is useful for calculating credit scores.<br>

Relation b/w Avg_Open_To_Buy, Credit_Limit and Avg_Utilization_Ratio:<br>

( Avg_Open_To_Buy / Credit_Limit ) + Avg_Utilization_Ratio = 1<br>
