# 📊 Customer Churn Analysis using Power BI

An end-to-end **Customer Churn Analysis** project built using a telecom dataset and visualized through **interactive Power BI dashboards**.  
This project helps identify **churn patterns, customer risk factors, and service-level impacts** to support data-driven business decisions.

---

## 🔍 Project Overview

Customer churn is a major challenge for subscription-based businesses. This project analyzes customer behavior across demographics, services, contracts, and payment methods to answer key business questions such as:

- Why do customers churn?
- Which customer segments are at higher risk?
- How do services and contract types influence churn?

The insights are delivered through **three dynamic Power BI dashboards** for better decision-making.

---

## 📁 Repository Structure

| File | Description |
|-----|------------|
| `Customer-Churn-Dataset.xlsx` | Telecom customer dataset with churn details |
| `Customer Churn Analysis.pbix` | Power BI report with dashboards, data model & DAX |

---

## 🧾 Dataset Description

The dataset contains customer-level information including:

### 👤 Customer Information
- `customerID`
- `gender`
- `SeniorCitizen`
- `Partner`
- `Dependents`

### 📄 Account Details
- `tenure`
- `Contract`
- `PaperlessBilling`
- `PaymentMethod`

### 📡 Services
- `PhoneService`
- `MultipleLines`
- `InternetService`
- `StreamingTV`
- `StreamingMovies`

### 🔐 Security & Support
- `OnlineSecurity`
- `OnlineBackup`
- `TechSupport`
- `DeviceProtection`

### 💰 Charges & Tickets
- `MonthlyCharges`
- `TotalCharges`
- `numAdminTickets`
- `numTechTickets`

### 🎯 Target Variable
- `Churn` (Yes / No)

---

## 📊 Dashboards Overview

### 1️⃣ Customer Churn Dashboard
Provides a high-level churn analysis including:
- Total churned customers
- Monthly & yearly revenue impact
- Churn distribution by tenure and gender
- Contract type & payment method influence
- Average monthly and total charges

**📌 Insight:**  
Customers with **month-to-month contracts** and **electronic check payments** show the highest churn.

---

### 2️⃣ Customer Risk Dashboard
Focuses on identifying customers with high churn probability:
- Churn rate by internet service type
- Monthly charges vs churn rate
- Admin & tech ticket comparison
- Contract duration impact

**📌 Insight:**  
Customers using **fiber optic internet**, having **high monthly charges**, and raising **frequent tech tickets** are more likely to churn.

---

### 3️⃣ Services Dashboard
Analyzes churn based on service usage:
- Internet service type
- Streaming TV & movies
- Phone service & multiple lines
- Online security, backup, tech support, and device protection

**📌 Insight:**  
Customers **without support and security services** show significantly higher churn rates.

---

## 🛠 Tools & Technologies

- **Power BI Desktop** – Data modeling & visualization  
- **DAX** – Measures, KPIs & calculations  
- **Microsoft Excel** – Data storage & preprocessing  

---

## 🎯 Key Business Insights

✔ Month-to-month contracts drive maximum churn  
✔ High monthly charges increase churn probability  
✔ Absence of support services raises churn risk  
✔ Long-term contracts (1-year, 2-year) reduce churn significantly  

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/kavi11662/Customer-Churn-Analysis.git
