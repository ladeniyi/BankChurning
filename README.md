# BankChurning
Hypothetical Scenario:  Credit card company X is trying to reduce customer churn rate. I have been brought on as Data Analytics Consultant at Company X. My goal is to identify customers who are unhappy and are at risk of churning before it is too late. 

My plan of action is analyze the demographic and financial data of clients at Company X to identify customers at risk of churning, build and evaluate the model, and use key results from my classification model  to highlight clients at risk of leaving, allowing Company X to truly focus on their retention efforts.

For this project, I will be working with the Credit Card Customers dataset stored in Credit Card Customers.csv
This dataset was taken from Kaggle (https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers?select=BankChurners.csv).
It includes 21 explanatory variables describing aspects of customers. Of the 21 features, 6 are categorical while the rest are numerical variables. My target varialbe is Attrition flag (1  for Attrited Customer and 0 for Existing Customer. A description for each feature can be found below.

1. CLIENTNUM: Client number. Unique identifier for the customer holding the account
2. Attrition Flag: Internal event (customer activity) variable - if the account is closed then 1 (Attrited Customer) else 0 (Existing Customer)
3. Customer Age: Demographic variable - Customer's Age in Years
4. Gender: Demographic variable - M=Male, F=Female
5. Dependent count: Demographic variable - Number of dependents
6. Education Level: Demographic variable - Educational Qualification of the account holder (high school, college, graduate, post-graduate, doctorate, uneducated, unknown)
7. Marital Status: Demographic variable (Married, Single, Divorced, Unknown)
8. Income Category: Demographic variable - Annual Income Category of the account holder (< $40K, $40K - 60K, $60K - $80K, $80K-$120K, > $120K, Unknown)
9. Card Category: Product Variable - Type of Card (Blue, Silver, Gold, Platinum)
10. Months on book: Period of relationship with bank in months
11. Total Relationship Count: Total no. of products held by the customer
12. Months Inactive 12 mon: No. of months inactive in the last 12 months
13. Contacts Count 12 mon: No. of Contacts in the last 12 months
14. Credit Limit: Credit Limit on the Credit Card
15. Total Revolving Bal: Total Revolving Balance on the Credit Card
16. Avg Open To Buy: Open to Buy Credit Line (Average of last 12 months)
17. Total Amt Chng Q4 Q1: Change in Transaction Amount (Q4 over Q1)
18. Total Trans Amt: Total Transaction Amount (Last 12 months)
19. Total Trans Ct: Total Transaction Count (Last 12 months)
20. Total Ct Chng Q4 Q1: Change in Transaction Count (Q4 over Q1)
21. Avg Utilization Ratio: Average Card Utilization Ratio

For this project, the following steps will be used:
1. Data munging and pre-processing
2. Explanotory data analysis (creation of data visualizaton to analyse the data)
3. Encode categorical variables
4. Create correlation matrix and heatmap 
5. Create a train and test split
7. Train classification models
8. Evaluate the models
