# bank-debit-credit-transaction-analysis
# 🏦 Bank Debit & Credit Transaction Analysis Dashboard
**(Tableau | SQL)**

## 📌 Project Overview

This project presents an **end-to-end Bank Debit & Credit Transaction Analytics solution**, built to analyze **transaction inflows, outflows, net cash flow, account activity, and high-risk transactions** using **SQL and Tableau**.

The dashboard enables financial teams and stakeholders to **monitor debit–credit trends, evaluate account behavior, identify high-risk transactions, and analyze performance across branches and banks**, supporting **financial monitoring and reconciliation use cases**.

The solution is designed from a **Data Analyst perspective**, focusing on **actionable financial insights rather than static reporting**.

---

## 🛠 Tools & Technologies Used

* **SQL**

  * Data extraction & transformation
  * Joins, aggregations, date functions
  * Business rule implementation

* **Tableau**

  * Interactive dashboards
  * Calculated fields & KPIs
  * Filters, parameters & drill-downs

---

## 📂 Dataset Description

The dataset contains **bank transaction–level data**, including:

* Transaction ID
* Transaction date
* Debit amount
* Credit amount
* Net transaction amount
* Account number
* Branch name
* Bank name
* Transaction method (Debit Card, Credit Card, Bank Transfer)
* Risk flag (High-risk transactions)

---

## 🧹 Data Cleaning & Transformation (SQL)

The following steps were performed to ensure **data quality and analytical usability**:

### **1️⃣ Data Validation**

* Ensured debit and credit values do not overlap per transaction
* Removed invalid or null transaction records

### **2️⃣ Date Processing**

* Converted transaction date to proper date format
* Extracted **Year, Quarter, Month, and Day**

### **3️⃣ Derived Metrics**

Created SQL-calculated fields:

* Total Debit Amount
* Total Credit Amount
* Net Transaction Amount
* Credit-to-Debit Ratio
* Account Activity Ratio

### **4️⃣ Aggregations**

* Monthly debit & credit trends
* Branch-wise and bank-wise transaction totals
* High-risk transaction counts

---

## 🧱 Data Modeling

* Created optimized SQL views for Tableau consumption

* Structured data for:

  * Time-based analysis
  * Account-level summaries
  * Risk analysis

* Ensured fast dashboard performance

---

## 📊 Key KPIs

The dashboard tracks the following KPIs:

* **Total Credit Amount**
* **Total Debit Amount**
* **Net Transaction Amount**
* **Account Activity Ratio**
* **Credit to Debit Ratio**
* **High-Risk Transaction Percentage**

---

## 📈 Visualizations & Analysis

The Tableau dashboard includes:

* 📉 **Credit vs Debit Trend (Monthly)**
* ⚠️ **High-Risk Transaction Trend**
* 🏦 **Branch Performance by Transaction Amount**
* 💳 **Transaction Method Distribution**
* 🏛 **Bank-wise Transaction Volume Analysis**
* 🔍 **Period-wise Drill-down Analysis**

---

## 🎛 Interactive Features

* Filters for:

  * Year
  * Quarter
  * Month
  * Day

* Dynamic KPIs responding to selections

* Drill-down enabled across time periods

---

## 💡 Business Insights & Use Cases

### **1️⃣ Cash Flow Monitoring**

Clear visibility into debit and credit movements helps assess **liquidity position**.

**Use Case:**
Daily and monthly financial monitoring.

---

### **2️⃣ High-Risk Transaction Tracking**

High-risk transaction trends help detect **potential fraud or abnormal behavior**.

**Use Case:**
Risk monitoring and compliance checks.

---

### **3️⃣ Branch & Bank Performance**

Identifies branches and banks contributing most to transaction volume.

**Use Case:**
Operational performance analysis and optimization.

---

## 🧠 Overall Strategic Insight

This project demonstrates how **SQL-driven data preparation combined with Tableau visualization** enables:

* Accurate transaction monitoring
* Early risk identification
* Improved financial transparency
* Data-driven decision-making

The dashboard acts as a **single source of truth for debit–credit transaction analysis**.

---

## 📸 Dashboard Preview

### 🔹 Tableau Dashboard Overview

 *![Tableau Dashboard](bank-debit-credit-dashboard.png)*

---

## 📁 Project Files

📂 **Tableau Workbook:**
*https://public.tableau.com/app/profile/apeksha.sonawane/viz/Projectbankanalytics_17681143735720/Dashboard1*

---

## 👤 Author

**Apeksha Sonawane**
Aspiring Data Analyst | SQL | Tableau | Business Analytics

⭐ *If you find this project useful, please consider starring the repository — it helps recruiters notice my work!*

---

