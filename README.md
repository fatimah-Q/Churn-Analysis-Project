📊 Customer Churn Analysis & Prediction
In today’s competitive business environment, retaining customers is crucial for long-term success. This project demonstrates a professional data science workflow to transform raw telecom data into actionable business intelligence using SQL Server, Python, and Power BI.

📌 Project Overview
Churn analysis is a key technique used to identify patterns and reasons behind customer departures. By leveraging advanced analytics and machine learning, this project predicts at-risk customers, allowing businesses to take proactive steps to improve customer satisfaction and loyalty.

🎯 Target Audience
While this project focuses on a telecom firm, the insights are applicable across various industries like Retail, Finance, and Healthcare, where customer retention is a priority.

🎯 Project Goals & Metrics
The goal was to create an entire ETL process in a database and a Power BI dashboard to achieve:

Visualize & Analyze: Deep dive into Demographic, Geographic, Payment & Account Info, and Services.

Churner Profile: Study profiles to identify areas for implementing marketing campaigns.

Future Prediction: Identify a method to predict future churners with 84% accuracy.

Key Metrics: Tracked Total Customers (6.418K), Total Churn & Churn Rate (26.99%), and New Joiners (411).

📂 Project Structure
Churn Prediction.ipynb: Python notebook for EDA and Random Forest modeling.

Churn_Queries.sql: SQL scripts for business logic and data cleaning.

Churn_Analysis_Dashboard.pbix: Interactive Power BI dashboard.

Customer_Data.csv: Source dataset with 6,000+ customer records.

📊 Dashboard Preview
Note: Below are the interactive dashboards developed to visualize customer behavior and predictions.

1. Summary Dashboard
   <img width="500" height="312" alt="Churn Analysis - Summery Dashboard" src="https://github.com/user-attachments/assets/032827f9-b8cb-44be-b9fe-902a9d4a1774" />

2. Prediction Dashboard
   <img width="553" height="329" alt="Churn Analysis - Prediction Dashboard" src="https://github.com/user-attachments/assets/fdecdee9-d527-4bfe-bacf-8a04bd19c91a" />

💡 Key Highlights & Insights
Churn Drivers: Identified that Contract Type and Monthly Charges are primary indicators of attrition.

Demographic Trends: Detailed segmentation by age and gender to pinpoint high-value target groups.

Actionable ROI: Data-driven recommendations for sustained business success.

🚀 How to Run
Execute Churn_Queries.sql in SQL Server to prepare database views.

Run Churn Prediction.ipynb to train the model and generate Predictions.csv.

Open Churn_Analysis_Dashboard.pbix in Power BI to explore the interactive reports.
