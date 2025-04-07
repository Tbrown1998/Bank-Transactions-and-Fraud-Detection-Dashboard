# 💳 Bank Transaction & Fraud Detection Dashboard Analysis (Using Power BI)
![Screenshot (82)](https://github.com/user-attachments/assets/513de2bb-10d2-48b6-951f-c45778643d79)

📌 **Live Dashboard Link**: [View Dashboard](https://app.powerbi.com/reportEmbed?reportId=YOUR_REPORT_ID)  

---

## 📌 Project Overview
This project focuses on analyzing **bank transactions** to detect fraudulent activities using **Power BI**. Fraud detection is crucial for financial institutions to mitigate risks and minimize financial losses. 

Using **Power BI’s data transformation (Power Query) and interactive visualizations**, this project:
- **Monitoring** bank transactions.
- **Identifies fraudulent transactions** based on patterns and anomalies.
- **Analyzes transaction trends** across different payment types, locations, and customer segments.
- **Builds an interactive fraud detection dashboard** for real-time monitoring and analysis.

---

## 🎯 Business Problem
### **🔎 Problem Statement**
Banks and financial institutions process **millions of transactions daily**, and fraudulent activities can often go undetected. Fraud detection must be **accurate and efficient** to reduce financial losses while minimizing disruptions to genuine customers.

The key challenges addressed in this project:
- **Detect fraudulent transactions** based on patterns, spending behaviors, and transaction anomalies.
- **Analyze transaction types** (e.g., withdrawals, online payments, wire transfers) to identify high-risk categories.
- **Provide actionable insights** using Power BI dashboards to enhance fraud monitoring.

---

## 📊 Dataset Information
The dataset contains **bank transaction records**, including both fraudulent and non-fraudulent transactions. It has been transformed using **Power Query in Power BI**.

| Column Name         | Description |
|---------------------|-------------|
| `Transaction_ID`   | Unique identifier for each transaction |
| `Sender_ID`      | Unique identifier for the sender |
| `Reciever_ID`      | Unique identifier for the receiver |
| `Transaction_Date` | Date and time of the transaction |
| `Transaction_Type` | Type of transaction (e.g., Deposit, Withdrawal, Transfer, Payment) |
| `Amount`          | Transaction amount in USD |
| `Transaction_Location` | Geographical location of the transaction |
| `Transaction Status` | Staus of transaction |
| `Fraud_Flag`     | `TRUE` = Fraudulent transaction, `FALSE` = Legitimate transaction |

---

## 🛠️ Tools & Technologies Used  
✔ **Power BI** - Data cleaning (Power Query), modeling, and visualization  
✔ **DAX (Data Analysis Expressions)** - Calculated measures for RFM scores  
✔ **Excel** - Initial dataset inspection and preprocessing 
- ![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoft-excel&logoColor=white) ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-F2C811?logo=powerbi&logoColor=black) ![Power Query](https://img.shields.io/badge/Power_Query-F2C811?logo=powerbi&logoColor=black)

---

## ⚡ Power BI Data Processing & Cleaning (Power Query)
### **1️⃣ Data Cleaning & Preprocessing**
✔ Removed **duplicate transactions** to ensure data integrity.  
✔ Converted `Transaction_Date` to **DateTime format** for accurate time-based analysis.  
✔ Handled **missing values** in merchant names and transaction locations.  
✔ Standardized **transaction categories** for consistency.  

### **2️⃣ Data Transformation & Modeling**
✔ Created **calculated columns** for fraud detection metrics.  
✔ Designed a **date table** for time-based analysis in Power BI.  
✔ Established **relationships** between transactions and customers for segmentation analysis.  

---

## 📊 Power BI Fraud Detection Dashboard
### Dashboard Overview:
![Screenshot (82)](https://github.com/user-attachments/assets/513de2bb-10d2-48b6-951f-c45778643d79)

### Fraud Detection Dashboard:
![Screenshot (83)](https://github.com/user-attachments/assets/31a08455-8649-4949-9b97-594730802907)

### Transaction Details Dashboard:
![Screenshot (117)](https://github.com/user-attachments/assets/f84c78f0-ffa9-40bb-a83c-31e4b06a1e6e)

 ### Explore the Interactive Dashboard**
- Use slicers to **filter transactions by date, type, and fraud status**.
- Hover over visuals to **view transaction trends and fraud patterns**.

📌 **Live Dashboard Link**: Click to [View Live Interactive Dashboard](https://app.powerbi.com/reportEmbed?reportId=YOUR_REPORT_ID)  


## 📈 Key Insights from Analysis
✅ **Fraudulent transactions are most common in Transfers.**  
✅ **Suspicious transactions often occur during non-business hours.**  
✅ **High-risk merchants and locations exhibit repeated fraud patterns.**  
✅ **Customer segmentation helps identify individuals with abnormal spending behavior.**  

---

## 🏆 Contribution Guidelines
🔹 If you find this project useful, **star** ⭐ the repository!  
🔹 Fork the repository and submit a **pull request** for improvements.  
🔹 Found an issue? **Open a discussion or issue** to suggest enhancements.  

---

## 📌 About Me
Hi, I'm Oluwatosin Amosu Bolaji, a Data Analyst with strong skills in Python, SQL, Power BI, and Excel. I turn raw data into actionable insights through automation, data storytelling, and visual analytics.

- **💡 Tools & Tech:** **Python** (Pandas, NumPy, Matplotlib, Seaborn) | **SQL** (MsSQL, Postgree, MySQL) | **Microsoft Power BI** | **Microsoft Excel**
- **🔹 Key Skills:** Data wrangling, dashboarding, reporting, and process optimization.
- ![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-2.0.0-150458?logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-1.21.0-013243?logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5.0-blue?logo=python&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-0.11.0-black?logo=python&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-5.5.0-3F4F75?logo=plotly)
- ![SQL](https://img.shields.io/badge/SQL-Server-red?logo=microsoft-sql-server&logoColor=white) ![MS SQL](https://img.shields.io/badge/Microsoft_SQL_Server-CC2927?logo=microsoft-sql-server&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
- ![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-F2C811?logo=powerbi&logoColor=black) ![Power Query](https://img.shields.io/badge/Power_Query-F2C811?logo=powerbi&logoColor=black)
- ![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoft-excel&logoColor=white)

#### 🚀 **Always learning. Always building. Data-driven to the core.**  

### 📫 **Let’s connect!**  
- 📩 oluwabolaji60@gmail.com
- 🔗 : [LinkedIn](https://www.linkedin.com/in/oluwatosin-amosu-722b88141)
- 🌐 : [My Portfolio](https://www.datascienceportfol.io/oluwabolaji60) 
- 𝕏 : [Twitter/X](https://x.com/thee_oluwatosin?s=21&t=EqoeQVdQd038wlSUzAtQzw)
- 🔗 : [Medium](https://medium.com/@oluwabolaji60)
- 🔗 : [View my Repositories](https://github.com/Tbrown1998?tab=repositories)
