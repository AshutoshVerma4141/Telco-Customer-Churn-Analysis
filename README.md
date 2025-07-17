📌 Telco Customer Churn Analysis Summary
🔹 1. Data Cleaning & Preparation
•	Dataset Size: 7043 rows × 21 columns.
•	Replaced blank entries in TotalCharges with 0 to avoid type conversion issues and converted it to float.
•	Transformed SeniorCitizen column from 0/1 → No/Yes for clarity.
________________________________________
🔹 2. Overall Churn Rate
•	📊 A pie chart revealed that 26.54% of customers have churned while 73.46% have stayed.
________________________________________
🔹 3. Key Churn Drivers Identified
Based on count plots and histograms, the following factors significantly influenced churn:
👵 Senior Citizens
•	Churn rate for senior citizens is much higher than for non-seniors.
•	Bar charts with % stacking showed a disproportionate exit rate among them.
📆 Contract Type
•	Month-to-month contract customers are at the highest risk:
o	A large majority of churned customers were using this type.
o	In contrast, 1- and 2-year contract holders had significantly lower churn.
💳 Payment Method
•	Customers using Electronic Check had the highest churn rate among all payment methods.
•	Automatic payment methods (like Bank Transfer or Credit Card) showed reduced churn.
🌐 Internet & Support Services
•	Customers using Fiber Optic internet churned more than those using DSL.
•	Lack of OnlineSecurity and TechSupport was strongly associated with churn:
o	Users without TechSupport had higher churn, possibly due to unresolved issues.
⏳ Tenure
•	Histogram analysis showed:
o	Customers with 1–2 months tenure had the highest churn rate.
o	Churn probability decreased steadily as tenure increased.
________________________________________
🔹 4. Feature-Wise Churn Analysis
Your analysis used 9 stacked bar charts comparing churn rates across features:
•	StreamingTV, OnlineSecurity, DeviceProtection, etc.
•	Key finding: Services like OnlineBackup and TechSupport play a crucial role in customer retention.
________________________________________
📌 Insights Recap
Feature	Key Insight
Churn Rate	26.54% of customers churned
Contract Type	Month-to-month users have highest churn
Senior Citizens	More likely to churn
Payment Method	Electronic Check → High churn
Internet Service	Fiber Optic users churn more
Tech Support	Lack of support = higher churn
Tenure	New users (0–2 months) churn more

