# Bank Loan Customer Analysis Dashboard

## Project Overview
This project focuses on analyzing **Bank Loan Customer Data** to evaluate **loan distribution, repayment behavior, credit risk, and customer verification impact**.  
The dashboard is designed to support **banking and financial analysis** by identifying **high-risk segments, strong repayment patterns, and regional loan trends**.

---

## Banking Use Case
This analysis supports key banking functions such as:
- **Credit risk assessment** across customer segments and regions
- **Loan portfolio performance monitoring**
- **Verification impact analysis** on repayment behavior
- **Customer segmentation** based on loan status and credit grade

---

## Key KPIs
- **Total Loan Amount:** 445.60M  
- **Total Funded Amount:** 434.81M  
- **Total Payment Collected:** 482.70M  
- **Total Revolving Balance:** 531.51M  

---

## Key Insights

### 1. State-wise Loan Distribution
- Loan disbursement is **concentrated in a limited number of states**, indicating regional dependency in lending.
- High-performing states contribute a significant portion of the total loan portfolio.

### 2. Verification Status vs Repayment
- **Verified customers contribute higher total payments** compared to non-verified customers.
- Verification status acts as a **strong indicator of repayment reliability**.

### 3. Loan Status Analysis
- Majority of loans fall under **Fully Paid** and **Charged Off** categories.
- Charged-off loans highlight areas requiring **stricter credit validation**.

### 4. Grade & Sub-Grade Risk Analysis
- **Lower credit grades (E, F, G)** show **higher revolving balances**, indicating increased default risk.
- Higher grades demonstrate **better repayment discipline**.

### 5. Home Ownership vs Payment Behavior
- Customers with **Mortgage and Rent** ownership types dominate repayment amounts.
- Home ownership status influences **payment consistency and credit stability**.

### 6. Year-wise Loan Trend
- Loan disbursement shows a **steady upward trend over the years**.
- Growth reflects increased borrowing demand and portfolio expansion.

---

## Dataset Information
- Loan transaction data covering multiple customers and regions
- Key attributes include:
  - State  
  - Loan Status  
  - Verification Status  
  - Grade and Sub-Grade  
  - Home Ownership  
  - Loan Amount  
  - Funded Amount  
  - Total Payment  
  - Revolving Balance  
  - Issue Year  

---

## Tools & Technologies

### Data & ETL
- **SQL** – Data extraction, joins, aggregations, and KPI calculations  
- **ETL Processes** – Data cleaning, transformation, and validation  

### Analytics & Visualization
- **Tableau** – Interactive dashboards, KPI cards, slicers, and trend analysis  
- **DAX** – Measures for financial and credit-related calculations  

---

## How to Use
1. Download the Power BI (`.pbix`) file from this repository  
2. Open the file using **Tableau Desktop**  
3. Use slicers to filter by **State, Loan Status, Grade, or Year**  
4. Analyze KPIs and visuals to extract **banking insights**

---

## Dashboard Preview
![Bank Loan Customer Analysis Dashboard](./assets/bank_loan_dashboard.png)

---

## Conclusion
This project demonstrates how **credit grade, verification status, geography, and customer profile** directly impact loan repayment and portfolio risk.  
The insights can help banks **reduce defaults, improve credit screening, and optimize lending strategies**.
