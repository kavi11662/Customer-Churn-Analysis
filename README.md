📊 Customer Churn Analysis – Power BI Dashboard

This project focuses on analyzing customer churn behavior using a telecom customer dataset and visualizing key insights through interactive Power BI dashboards. The goal is to identify churn patterns, risk factors, and service-level impacts to support data-driven decision-making.

🔍 Project Overview

Customer churn is a critical business problem where customers stop using a company’s services. In this project, I analyzed customer demographics, services, contracts, and payment behavior to understand:

Why customers churn

Which customer segments are at higher risk

How services and contract types affect churn

The analysis is presented using three interactive Power BI dashboards.

📁 Files in This Repository

Customer-Churn-Dataset.xlsx
Raw dataset containing customer details, service usage, charges, tickets, and churn status.

Customer Churn Analysis.pbix
Power BI file containing all dashboards, data model, and DAX measures.

🧾 Dataset Description

The dataset includes the following key attributes:

Customer Info: customerID, gender, SeniorCitizen, Partner, Dependents

Account Details: tenure, Contract, PaperlessBilling, PaymentMethod

Services: PhoneService, MultipleLines, InternetService, StreamingTV, StreamingMovies

Security & Support: OnlineSecurity, OnlineBackup, TechSupport, DeviceProtection

Charges: MonthlyCharges, TotalCharges

Tickets: numAdminTickets, numTechTickets

Target Variable: Churn (Yes / No)

📊 Dashboards Included
1️⃣ Customer Churn Dashboard

Provides an overall churn analysis with:

Total churned customers

Monthly & yearly charges

Churn by tenure

Churn by gender

Contract type and payment method impact

Average monthly and total charges

📌 Key Insight:
Customers with month-to-month contracts and electronic check payments show the highest churn.

2️⃣ Customer Risk Dashboard

Focuses on identifying high-risk churn customers:

Churn rate by internet service type

Monthly charges vs churn rate

Admin & tech tickets comparison

Contract duration impact on churn

📌 Key Insight:
Customers using fiber optic internet with high monthly charges and frequent tech tickets are more likely to churn.

3️⃣ Services Dashboard

Analyzes churn based on service usage:

Internet service type

Streaming TV & movies

Phone service & multiple lines

Online security, backup, tech support, and device protection

📌 Key Insight:
Customers without security, backup, or tech support services have higher churn rates.

🛠 Tools & Technologies Used

Power BI Desktop – Data modeling & visualization

DAX – Calculated measures and KPIs

Excel – Dataset storage and preprocessing

🎯 Key Business Insights

Month-to-month contracts drive maximum churn

High monthly charges increase churn probability

Lack of support services (Tech Support, Online Security) increases churn

Long-term contracts (1-year, 2-year) significantly reduce churn

🚀 How to Use This Project

Clone the repository:

git clone https://github.com/kavi11662/Customer-Churn-Analysis.git


Open Customer Churn Analysis.pbix in Power BI Desktop

Interact with filters and slicers to explore insights

📌 Conclusion

This project demonstrates how customer churn can be analyzed effectively using Power BI. The dashboards help businesses identify churn drivers, evaluate customer risk, and improve retention strategies through data-driven insights.

👤 Author

Kavi
Power BI | Data Analytics
GitHub: https://github.com/kavi11662
