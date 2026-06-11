# Superstore Sales Analysis (Task 3)

## Overview
This project analyzes the Superstore sales dataset (2014–2017) using SQL for data analysis and Power BI for visualization, concluding with a written business analysis report.

## Project Files

| File | Description |
|------|-------------|
| `3rd_task__.csv` | Raw transactional sales dataset (orders, sales, profit, discount, region, category, segment, etc.) |
| `3rd_task_sql.pdf` | SQL queries and outputs for the analysis tasks |
| `Task3rd_power_bi.pbix` | Power BI dashboard built on the dataset |
| `Business_Analysis_Report.docx` | Final 2–3 page business analysis report (Part D) |

## SQL Analysis (Part A–C)
1. **Monthly Performance Analysis** – Aggregates monthly sales and profit using `YEAR()` and `MONTH()` on `Order Date`.
2. **Growth Rate Calculation** – Uses a CTE with self-joins to calculate month-over-month sales growth percentage.
3. **Business Classification (CASE)** – Classifies each order as High/Medium/Low Value based on sales thresholds.
4. **Underperforming Regions** – Groups profit by region with `HAVING` to identify regions below a profit threshold.

## Power BI Dashboard
Visualizes monthly sales trends, regional profitability, category performance, discount impact, and customer segment contribution.

## Business Analysis Report (Part D)
The Word report answers six key business questions:
1. Is the company growing month-over-month?
2. Which region is underperforming?
3. Which category has the highest growth?
4. Are discounts reducing profit?
5. Which customer segment contributes most revenue?
6. What strategic actions should management take?

### Key Findings
- Total Sales: **$9,188,803.44** | Total Profit: **$572,794.04** (~6.2% margin)
- **East** region is the most underperforming (-$1,071.85 profit)
- **Technology** is the strongest category (~17.4% margin); **Furniture** is weakest (~2.5% margin)
- Discounts of **30%+ consistently reduce profit** to negative levels
- **Consumer** segment drives the most revenue and profit (~49% of sales)

## How to Use
1. Open `3rd_task_sql.pdf` to review SQL logic and outputs.
2. Open `Task3rd_power_bi.pbix` in Power BI Desktop for interactive visuals.
3. Read `Business_Analysis_Report.docx` for the full written analysis and recommendations.

## Tools Used
- MySQL Workbench (SQL queries)
- Power BI Desktop (dashboard)
- Microsoft Word (final report)
