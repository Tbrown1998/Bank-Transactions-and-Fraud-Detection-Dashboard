# 💳 Bank Transaction & Fraud Detection Dashboard (Power BI)
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
✔ **DAX (Data Analysis Expressions)** - Calculated measures and columns for fraud analysis  
✔ **Excel** - Initial dataset inspection and basic cleaning  

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

![Screenshot (83)](https://github.com/user-attachments/assets/e5cf58d0-af92-40d2-b75d-16201bc72378)


📌 **Live Dashboard Link**: [View Dashboard](https://app.powerbi.com/reportEmbed?reportId=YOUR_REPORT_ID)  

 ### Explore the Interactive Dashboard**
- Use slicers to **filter transactions by date, type, and fraud status**.
- Hover over visuals to **view transaction trends and fraud patterns**.

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
Hi, I'm Oluwatosin Amosu Bolaji, a Data Analyst skilled in SQL, Power BI, and Excel. I enjoy turning complex datasets into actionable insights through data visualization and business intelligence techniques.

- **🔹 Key Skills:** Data Analysis | SQL Queries | Power BI Dashboards | Data Cleaning | Reporting
- **🔹 Passionate About:** Data storytelling, problem-solving, and continuous learning

#### 🚀 **Always learning and improving—driven by curiosity and a passion for analytics.**  

### 📫 **Let’s connect!**  
- 📩 oluwabolaji60@gmail.com
- 🔗 : [LinkedIn](https://www.linkedin.com/in/oluwatosin-amosu-722b88141)
- 🌐 : [My Portfolio](https://www.datascienceportfol.io/oluwabolaji60) 
- 𝕏 : [Twitter/X](https://x.com/thee_oluwatosin?s=21&t=EqoeQVdQd038wlSUzAtQzw)
- 🔗 : [Medium](https://medium.com/@oluwabolaji60)
