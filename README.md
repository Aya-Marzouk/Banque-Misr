# 🏦 Banque Misr Banking Analysis Dashboard

## 📌 Project Overview
This project delivers a multi-page interactive **Power BI Dashboard** analyzing
the banking operations of **Banque Misr** — one of Egypt's leading financial institutions.
Built entirely in **Microsoft Power BI**, the dashboard leverages **Power Query** for 
data transformation and cleaning, and **DAX (Data Analysis Expressions)** for dynamic 
KPI calculations, time intelligence measures, and advanced aggregations across all pages.

The dashboard covers customer segmentation, transaction behavior, loan portfolio analysis,
branch performance, and payment channels, providing a comprehensive view of the bank's
operational health and customer base.

---

## 📂 Dataset
- **Source:** Banque Misr Internal Banking Dataset
- **Content:** Data on customers, transactions, loans, branches, payments, and investments.

**Key metrics analyzed:**
- Total Customers, Transactions & Average Installment
- Loan Portfolio (Total, Active, Average Amount)
- Customer Segmentation (Retail, Mass, VIP)
- Transaction Types by Month & Quarter
- Branch Distribution across Egyptian cities
- Transaction Channels (ATM, Branch, Online)

---

## 📊 Dashboard Preview

<img width="902" height="498" alt="image" src="https://github.com/user-attachments/assets/b6885196-8997-4629-b736-8ef7d9c5189c" />
<img width="896" height="501" alt="image" src="https://github.com/user-attachments/assets/7113b867-9a89-431e-96e5-ee1b771508b2" />
<img width="907" height="507" alt="image" src="https://github.com/user-attachments/assets/3ab96cee-8bfd-4e2d-b85d-3ea56ab82086" />
<img width="889" height="498" alt="image" src="https://github.com/user-attachments/assets/7c845e64-9e37-4ebd-944f-20582c9eb74b" />
<img width="895" height="497" alt="image" src="https://github.com/user-attachments/assets/f15e0be4-6db6-4d23-a621-ea09a69bca36" />



---

## 📑 Dashboard Pages

### 🏠 Page 1 — Cover
*Branded landing page introducing the Banque Misr Banking Analysis project,
featuring the official logo and a brief description of the bank's mission.*

---

### 📊 Page 2 — Dashboard (Overview)
**KPIs:**
- 1K Total Customers | 4K Total Transactions | 6.59K Avg Installment

**Visuals:**
- Line chart: Transaction Types by Month (Jan–Jun) — tracking Deposit, Payment, Transfer & Withdrawal trends
- Summary table: Quarterly breakdown (Q1–Q4 2024) showing Withdrawals Count, Total Transactions, Deposits Value & Deposits Count
- Components filter panel: Deposit / Payment / Transfer / Withdrawal
- Services filter: ATM / Branch / Online

---

### 👥 Page 3 — Accounts (Customer Analysis)
**KPIs:**
- 100 VIP Customers | 38.63K Avg Monthly Income | 45.03 Avg Customer Age

**Visuals:**
- Pie chart: Total Customers by Segment — Retail (60%), Mass (30%), VIP (10%)
- Horizontal bar chart: Customer count per segment (Retail, Mass, VIP)
- Map: Total Customers by City across Egypt
- Filters: City (Alexandria, Assiut, Cairo, Giza), Gender (Female, Male), Segment (Mass, VIP, Retail)

---

### 💳 Page 4 — Payments (Transaction Analysis)
**KPIs:**
- 4K Total Transactions | 74M Total Transaction Value | 330 Monthly Transactions

**Visuals:**
- Bar chart: Total Transactions by Quarter (Q1–Q4) — consistent volume across all quarters
- Horizontal bar chart: Total Branches by City (Cairo, Giza, Mansoura, Assiut, Alexandria, Tanta)
- Map: Branch locations across Egypt ("Our Branches")
- Donut chart: Total Transactions by Channel — ATM (34%), Online (34%), Branch (32%)
- Filters: City, Transaction Type (Deposit, Payment, Transfer, Withdrawal), Channel (ATM, Branch, Online)

---

### 💰 Page 5 — Loans
**KPIs:**
- 600 Total Loans | 391 Active Loans | 395.67K Avg Loan Amount

**Visuals:**
- Horizontal bar chart: Total Loans by Loan Type (Personal, Car, Mortgage)
- Donut chart: Total Loans by Status — Active (65.17%), Defaulted (26.5%), Closed (8.33%)
- Area chart: Total Loans Portfolio by Year (2023–2029)
- Filters: Loan Type (Car, Mortgage, Personal), Loan Status (Active, Closed, Defaulted)

---

## 🎯 Objectives
- Monitor overall banking activity through key customer and transaction KPIs.
- Analyze monthly and quarterly transaction trends across all service types.
- Segment the customer base by demographics, city, gender, and segment tier.
- Evaluate the loan portfolio health — tracking active, closed, and defaulted loans.
- Map branch distribution and assess performance across Egyptian cities.
- Provide data-driven insights to support strategic banking decisions.

---

## 🛠 Tech Stack
- **Visualization:** Microsoft Power BI (DAX, Power Query, Maps, Slicers, KPI Cards)
- **Data Modeling:** Star schema with related tables for Customers, Transactions, Loans & Branches
- **Data Source:** Excel / CSV
- **File Format:** `.pbix`

---

## 🔄 Project Workflow
1. **Data Cleaning:** Standardizing customer segments, loan statuses, transaction types,
   and city names using Power Query.
2. **Data Modeling:** Building relationships between Customers, Transactions, Loans,
   Branches, and Date tables.
3. **DAX Measures:** Creating KPIs for Total Customers, Total Transactions, Avg Installment,
   Active Loans, Avg Loan Amount, Monthly Transactions, and Total Transaction Value.
4. **Dashboard Development:** Designing a 5-page Power BI report with a branded cover,
   navigation sidebar, interactive slicers, maps, and dynamic visuals.

---

## 📊 Key Insights

- **Customers:** The bank serves **1,000 customers** — **503 Female** and **497 Male**,
  with an average age of **45** and average monthly income of **38.63K**.
- **Segmentation:** Retail customers make up the majority at **60%**,
  while VIP customers represent a premium segment of **10%** (100 customers).
- **Transactions:** **4,000 total transactions** were recorded in 2024,
  with consistent quarterly volumes and relatively even channel distribution
  across ATM, Branch, and Online.
- **Loans:** Out of **600 total loans**, **391 are active (65.17%)**,
  with Personal loans leading by volume and an average loan amount of **395.67K**.
- **Branches:** Cairo holds the highest branch count, followed by Giza and Mansoura,
  reflecting the bank's concentration in major urban centers.

📌 **Key Insight:** The high proportion of active loans combined with a 26.5% defaulted
loan rate signals an opportunity for improved credit risk assessment and customer
follow-up strategies.

---

## 📂 Repository Structure
* 📂 **1- Data Source:** Raw data files (Excel/CSV).
* 📂 **2- Power BI Dashboard:** Interactive `.pbix` file.
* 📂 **3- Dashboard Images:** Screenshots of all 5 dashboard pages.

---

## 📫 Connect with Me
**Aya Ahmed**
* LinkedIn: https://www.linkedin.com/in/aya-a7med/
* Email: aya.ibrahim.official.2@gmail.com

---

## ⭐️ Support
If you found this project useful, give it a ⭐️ on GitHub!
