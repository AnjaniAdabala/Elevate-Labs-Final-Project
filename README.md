
# Financial KPI Analysis for a Startup

## 📌 Overview
This project analyzes key financial metrics for a startup, focusing on revenue, expenses, customer acquisition cost (CAC), lifetime value (LTV), and burn rate. 
The goal is to visualize financial health and growth trends, helping business stakeholders make data-driven decisions.

## 🎯 Objectives
- Track monthly revenue and expenses
- Calculate and visualize key KPIs (CAC, LTV, LTV:CAC Ratio, Burn Rate)
- Build an interactive dashboard using Tableau
- Provide actionable insights for business strategy

## 🗂️ Dataset
A simulated dataset of startup financials for 8 months was created with the following columns:
- `Month`
- `Revenue ($)`
- `Expenses ($)`
- `Customers`
- `New_Customers`
- `Marketing_Spend ($)`
- Calculated columns: `Burn_Rate ($)`, `CAC ($)`, `ARPC ($)`, `LTV ($)`, `LTV_CAC_Ratio`

## 🔧 Tools Used
- **Excel**: Data preparation and calculations
- **Python (Pandas, Matplotlib)**: Optional statistical analysis and plots
- **Tableau**: Dashboard and visualization

## 📊 Key Metrics
- **Burn Rate:** Expenses - Revenue
- **Customer Acquisition Cost (CAC):** Marketing Spend / New Customers
- **Average Revenue per Customer (ARPC):** Revenue / Customers
- **Lifetime Value (LTV):** ARPC * 12 months
- **LTV:CAC Ratio:** LTV / CAC
- **Monthly Growth Rate:** ((Current Revenue - Previous Revenue) / Previous Revenue) * 100

## 🚀 Steps Followed
1. Created an Excel dataset with startup financials for 8 months.
2. Calculated KPIs in Excel with formulas.
3. Performed optional data analysis in Python for quick stats.
4. Built Tableau dashboard with:
   - KPI Cards (Revenue, Expenses, CAC, LTV:CAC Ratio)
   - Line Chart for Revenue vs Expenses
   - Bar Chart for CAC by Month
   - Scatter Plot for LTV vs CAC
5. Generated insights and prepared a PDF report.

## 📈 Insights
- Revenue shows steady growth, with a healthy **LTV:CAC ratio > 3**.
- Burn rate is reducing over time, indicating controlled expenses.
- CAC spikes in certain months, suggesting optimization opportunities in marketing.

## 📝 Deliverables
- `Startup_Financial_KPI_Analysis.xlsx` (dataset with formulas)
- Tableau Dashboard (`.twbx` file)
- 1–2 page Project Report (PDF)

## 🏁 Conclusion
This project demonstrates financial performance tracking for a startup using simple yet powerful analytics tools. 
The dashboard helps stakeholders monitor growth, optimize spending, and plan future strategies effectively.
