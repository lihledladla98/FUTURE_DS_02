# 📈 Sales Performance & Trends Analysis
## Data Science & Analytics — Task 2 (2026)
### By Future Interns | Thembelihle Dladla

---

## 📌 Project Overview

This project analyzes 7,043 Telco customer records to understand why customers leave, which segments are at highest risk, and what retention strategies can reduce churn. Customer churn analysis is one of the highest-impact areas in data science reducing churn directly increases monthly recurring revenue.

> **Dataset:** Superstore Sales Dataset  
> **Tool:** Microsoft Power BI Desktop  
> **Pages:** 2 Interactive Dashboard Pages  

---

## 🎯 Business Questions Answered

- How do sales and profit change over time?
- Which regions and segments drive growth?
- Which products generate high revenue but low profit?
- What are the key trends in business performance?
- Where can the business improve profitability?

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|--------|-------|
| 💰 Total Sales | $2.30M |
| 📈 Total Profit | $286K |
| 📦 Total Orders | 9,994 |
| 📊 Profit Margin | 12.4% |
| 📅 Time Period | 2014–2017 |

---

## 📁 Dashboard Structure

### 📄 Page 1 — Sales Overview
High-level performance summary across regions, categories, and time.

**Visuals included:**
- KPI Cards — Total Sales, Profit, Orders, Profit Margin  
- Sales Trend Over Time (Line Chart)  
- Sales by Region (Bar Chart)  
- Sales by Category (Donut Chart)  

---

### 📄 Page 2 — Churn Driver Analysis
Deep dive into the top factors causing customer churn.

**Visuals included:**
- Top Churn Risk Factors (Horizontal Bar Chart)  
- Churn by Contract Type (Table with risk color coding)  
- Churn by Tenure Band (Table) 
- Churn by Online Security (Table)
- Churn by Internet Service (Table)
-   
---

## 🔍 Key Findings

### 1. 📈 Sales Show Consistent Growth
Sales increase over time, indicating steady business growth.

### 2. 🌍 Regional Performance Varies
Some regions outperform others significantly in both sales and profit.

### 3. 📦 High Sales ≠ High Profit
Certain categories generate strong sales but lower profit margins.

### 4. 👥 Consumer Segment Leads
The Consumer segment contributes the highest sales.

### 5. 📉 Profit Fluctuations
Profit trends fluctuate, suggesting cost or pricing challenges.

---

## ⚡ Business Recommendations

| Priority | Area | Action | Expected Impact |
|----------|------|--------|----------------|
| 🥇 1 | Profitability | Optimize pricing for low-margin products | 📈 Higher profit |
| 🥈 2 | Growth | Focus on high-performing regions | 📈 Increased sales |
| 🥉 3 | Product Mix | Promote high-margin products | 📈 Better margins |
| 4️⃣ | Cost Control | Reduce operational inefficiencies | 📈 Improved profit |
| 5️⃣ | Customer Strategy | Target high-value segments | 📈 Better ROI |

---

## 🛠 Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard & visualization |
| **DAX** | Measures & calculations |
| **Power Query** | Data cleaning |
| **Excel** | Data exploration |

---

## 📐 DAX Measures Created

- Total Sales  
- Total Profit  
- Profit Margin  
- Total Orders  
- Sales Trend  
- Profit Trend  

- Source: IBM Sample Datasets / Kaggle
- Size: 7,043 rows × 21 columns
- Null values: 11 in TotalCharges (filled with MonthlyCharges)
  
---


## 🔄 Power Query Transformations

- Cleaned dataset  
- Converted date formats  
- Created time-based features (Year, Month)  
- Structured categories  

---

## 🚀 How to Use This Dashboard

1. Download `Task_2.pbix`  
2. Open in Power BI Desktop  
3. Navigate between pages  
4. Use filters to explore insights  

---

## 📂 Repository Structure
Task-2-Sales-Performance-Analysis/
│
├── dashboard/
│ └── Task_2.pbix
│
├── data/
│ └── superstore.xlsx
│
├── visuals/
│ ├── page1_screenshot(17).png
│ └── page2_screenshot(18).png
│
└── README.md


---
**Business Impact Summary**

📊 Current State
   Churn Rate          :  26.5%   (industry avg 15-20%)
   Monthly Rev Lost    :  $139,130
   Annual Rev Lost     :  ~$1.67M

🎯 After Recommendations
   Target Churn Rate   :  ~17%    (35-40% reduction)
   Monthly Rev Saved   :  ~$48,000
   Annual Rev Saved    :  ~$576,000+

📌 Bottom Line
   Fixing onboarding + converting MTM to annual +
   enabling auto-pay = 35-40% churn reduction,
   recovering $50K+/month in lost MRR.

---
## 👤 Author

**Thembelihle Dladla**

---

## 🏢 Program

This project was completed as part of the Future Interns Data Science & Analytics internship program. Analysis based on the   publicly available IBM Telco Customer Churn dataset.
