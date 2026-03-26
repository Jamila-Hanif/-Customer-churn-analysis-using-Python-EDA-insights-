# -Customer-churn-analysis-using-Python-EDA-insights- 
1. Business Problem
Customer churn presents a significant hurdle for businesses reliant on subscriptions. The primary objective of this analysis is to understand the reasons behind customer departures and to identify patterns that can help mitigate this churn.
2. Dataset Overview
The analysis utilises the WA_Fn-UseC_-Telco-Customer-Churn.csv dataset. This dataset comprises information on customer demographics, the services they subscribe to, their account details, and crucially, whether they have churned.
3. Data Cleaning
The following data cleaning procedures were carried out:
The TotalCharges column was converted to a numeric format, with any non-convertible entries being coerced to NaN.
Missing values within the TotalCharges column were imputed using the median value of the column.
The Churn target variable was encoded into a binary format, where 'Yes' is represented as 1 and 'No' as 0.
The customerID column was removed as it was deemed irrelevant for the analysis.
4. Exploratory Data Analysis (EDA)
A series of visualisations were generated to explore the factors influencing churn:
Churn Distribution: A bar chart illustrating the proportion of customers who churned versus those who did not.
Churn by Contract Type: A bar chart comparing churn rates across different contract durations (Month-to-month, One year, Two year).
Tenure vs. Churn: A box plot examining the relationship between a customer's tenure with the company and their likelihood to churn.
Monthly Charges vs. Churn: A box plot investigating the correlation between the monthly charges a customer pays and their propensity to churn.
5. Key Insights
Contract Type: Customers on month-to-month contracts exhibit a higher tendency to churn.
Tenure: Customers who have been with the company for a shorter period are at a greater risk of churning.
Monthly Charges: A higher monthly charge appears to correlate with an increased likelihood of churn.
6. Recommendations
Encourage Long-Term Contracts: Implement measures to incentivise customers to commit to longer contract periods.
Provide Onboarding Support: Offer enhanced support and guidance to new customers during their initial engagement with the company.
Targeted Discounts: Consider offering bespoke discounts or special promotions to customers who incur high monthly charges and are identified as being at high risk of churning.
7. Conclusion
Through a thorough analysis of customer behaviour and service utilisation, this project has identified the principal drivers of customer churn. By implementing the recommended strategies, the company can expect to improve customer retention rates and, consequently, boost revenue.
