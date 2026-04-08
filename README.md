This project analyzes customer churn behavior in a telecom dataset to identify key factors that influence customer retention and churn.

The goal is to help businesses reduce churn by understanding customer patterns and behavior.

Tech Stack
Python
Pandas
Matplotlib
Seaborn

Data Cleaning
Converted TotalCharges to numeric format
Handled missing values using median imputation
Converted Churn column into numeric (0 = No, 1 = Yes)
Created readable churn labels

Analysis Performed
Churn rate calculation
Contract type vs churn
Monthly charges vs churn
Tenure vs churn
Internet service impact
Payment method analysis
Demographic analysis (gender, senior citizens)

Visualizations
Churn distribution (bar & pie chart)
Monthly charges vs churn (boxplot)
Contract type vs churn
Tenure distribution by churn
Internet service & payment method analysis
Correlation heatmap

Key Insights
Customers with higher monthly charges are more likely to churn
Customers with shorter tenure have higher churn rates
Month-to-month contracts show the highest churn
Long-term contracts reduce churn significantly

Business Recommendations
Focus on retaining new customers early
Offer discounts for long-term contracts
Target high-paying customers with retention offers

Outputs
Cleaned dataset
Summary statistics
Multiple visualizations
Business insights report
