# 🏦 Banking Analytics Dashboard (Power BI)

## 📌 Project Overview

This project presents an **interactive Banking Analytics Dashboard** developed using **Power BI Desktop**. The dashboard provides a consolidated view of a bank’s customer portfolio, loans, and deposits, enabling stakeholders to monitor financial performance, understand customer distribution, and support data-driven decision-making.

The dataset represents a **snapshot of banking clients**, and the dashboard is designed to simulate real-world banking KPIs commonly used by analysts and management teams.
---

## 🎯 Problem Statement

Banks manage large volumes of customer and financial data across multiple products such as loans, deposits, savings, and business lending. However:

* Data is often scattered across tables and reports
* Decision-makers lack a unified view of key metrics
* Identifying risk exposure, loan concentration, and deposit structure becomes difficult

**The challenge** is to transform raw banking data into a clear, insightful, and interactive dashboard that supports quick analysis and strategic decisions.

---

## 💡 Proposed Solution

To address these challenges, this project:

* Integrates customer-level banking data into Power BI
* Uses **DAX measures** to calculate core banking KPIs
* Provides interactive filters (slicers) for dynamic analysis
* Presents financial metrics in a clean, professional dashboard layout

The solution focuses on **clarity, accuracy, and usability**, following industry-standard BI practices.

---

## 🧩 Key Features & Functionality

### 🔹 KPI Metrics

The dashboard includes key banking indicators such as:

* **Total Clients** – Overall customer count
* **Total Loan** – Combined exposure from:

  * Bank Loans
  * Business Lending
  * Credit Card Balances
* **Total Deposits** – Aggregated value of:

  * Checking Accounts
  * Savings Accounts
  * Term Deposits
* **Business Lending** – Total business loan exposure
* **Checking & Savings Accounts** – Individual account balances

All KPIs are implemented as **DAX Measures**, ensuring they dynamically respond to filters.

---

### 🔹 Interactive Slicers

* **Gender** – Analyze financial metrics by gender
* **Joining Year** – Simulated reporting year for comparative analysis

These slicers allow users to drill into specific customer segments.

---

### 🔹 Dashboard Navigation

* Loan Analysis
* Deposit Analysis
* Summary View

Navigation buttons enable a structured analytical flow, similar to enterprise dashboards.

---
## 📊 Dashboard Preview

### 🔹 Summary Dashboard
<img width="1293" height="740" alt="image" src="https://github.com/user-attachments/assets/2ac019aa-2b02-427a-8b32-16eafdc404f2" />


### 🔹 Loan Analysis
<img width="1298" height="727" alt="image" src="https://github.com/user-attachments/assets/b71c0fdb-8673-4003-a52c-7a599d73add3" />


### 🔹 Deposit Analysis
<img width="1298" height="724" alt="image" src="https://github.com/user-attachments/assets/8ec00e9d-ee74-4e8c-9ae4-1fd51bdb8a32" />

### 🔹 Summary
<img width="1298" height="725" alt="image" src="https://github.com/user-attachments/assets/f55f5ff3-c07a-483d-adff-f8400175e9b7" />

## 🛠️ Tools & Technologies Used

* **Power BI Desktop** – Data modeling, DAX, and visualization
* **DAX (Data Analysis Expressions)** – Measure creation and calculations
* **CSV Dataset** – Source data

---

## 🗂️ Data Description

The dataset includes customer-level information such as:

* Demographics (Gender, Nationality, Occupation)
* Financial attributes (Loans, Deposits, Account Balances)
* Risk and classification indicators

---

## 📊 Key DAX Measures (Examples)

* **Total Loan** = Bank Loan + Business Lending + Credit Card Balance
* **Total Deposits** = Checking + Savings + Term Deposits
* **Loan to Deposit Ratio** (optional KPI)

These measures are designed following best practices to ensure scalability and accuracy.

---

## 🎨 Dashboard Design Principles

* Neutral background for reduced visual noise
* Consistent KPI card sizing and alignment
* Standardized units (Millions / Billions)
* Minimal color palette following banking UI conventions

---

## 📈 Business Insights Enabled

* Loan vs deposit comparison
* Identification of high-value customer segments
* Business lending exposure analysis
* Portfolio-level financial overview

---

## 🚀 Future Enhancements

* Integration of real transaction-level time-series data
* Year-over-Year (YoY) and Month-over-Month (MoM) trend analysis
* Risk-weighted asset calculations
* Deployment to Power BI Service



## 🧠 Learning Outcomes

* Practical experience with Power BI and DAX
* Understanding of banking KPIs and financial analytics
* Hands-on dashboard design and data modeling
* Real-world BI problem-solving approach


