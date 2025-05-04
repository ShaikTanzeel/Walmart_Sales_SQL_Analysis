# SQL + Power BI Project: Walmart Sales Analysis

## 📊 Overview
This project explores Walmart sales data using SQL and Power BI to uncover valuable business insights. The goal is to demonstrate real-world data analytics skills by performing end-to-end analysis and presenting findings visually.

---

## 🎯 Objectives
- Perform data wrangling and feature engineering using SQL
- Analyze product performance, customer behavior, and revenue trends
- Use Power BI to visualize KPIs and build an interactive dashboard

---

## 🛠 Tools & Technologies
- **SQL** (MySQL Workbench) — for querying and analysis
- **Power BI** — for visualization
- **GitHub** — for version control and project sharing
- **Dataset** — [Walmart Sales Data from Kaggle](https://www.kaggle.com/datasets/prathamsharma123/walmart-sales-data)

---

## 🧱 Database Setup
**Steps:**
1. Created `walmart_sales` database
2. Designed `sales` table based on CSV structure
3. Imported `WalmartSalesData.csv` into MySQL Workbench

---

## 🧪 SQL Analysis (Learn-by-Doing)
### 🔹 Feature Engineering
- Added `time_of_day` column → Categorizes transactions as Morning, Afternoon, or Evening
- Extracted `day_name` and `month_name` from `date` field

### 🔹 Product Analysis
- Counted unique product lines
- Identified highest selling product lines
- Assigned "Good" or "Bad" based on average quantity sold
- Computed average rating per product line
- Found most popular lines by gender

### 🔹 Revenue & Tax Analysis
- Calculated monthly revenue (`SUM(total)`)
- Found month with highest `COGS`
- Determined highest revenue product line
- Identified product lines with highest VAT (`AVG(tax_pct)`)
- Ranked cities and branches by revenue

### 🔹 Customer Insights
- Counted payment methods and customer types
- Analyzed purchase frequency and VAT by customer type
- Tracked gender distribution per branch
- Evaluated ratings by time of day, branch, and weekday

### 🔹 Sales Patterns
- Counted sales by time_of_day and day_name
- Assessed busiest branches and revenue-driving customers

---

## 💡 Sample Business Questions Answered
- Which branch generates the most revenue?
- What product line performs best overall?
- Do customers prefer shopping in the evening or morning?
- What day of the week sees the highest customer satisfaction?

---

## 📁 Repository Structure
```
walmart-sales-sql-project/
├── README.md                      # Project documentation
├── data/
│   └── WalmartSalesData.csv      # Source dataset
├── walmart_sales_analysis.sql    # SQL queries step-by-step
└── visuals/                      # Power BI screenshots (optional)
```

---

## ✅ Next Steps
- Finalize and export Power BI dashboard
- Upload visual insights to `/visuals/` folder
- Share GitHub link on resume and LinkedIn

> 🔗 This project is designed to be portfolio-ready — clear, structured, and impactful.