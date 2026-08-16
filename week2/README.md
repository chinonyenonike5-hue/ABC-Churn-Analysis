# Week 2 – Business Intelligence & Interactive Dashboard Development

**Programme:** AnalystLab Africa – Data Analytics Internship
**Tool:** Microsoft Power BI
**Dataset:** [Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## Business Scenario

As a Junior Business Intelligence Analyst at AnalystLab Africa Consulting, this project builds an executive dashboard for a national retail company to monitor sales performance, profitability, customer behavior, and regional performance.

## Objective

Transform raw retail transaction data into an interactive Power BI dashboard that answers key business questions and supports data-driven decision-making for senior management.

## What's in this folder

| File | Description |
|---|---|
| `Superstore_Cleaned.csv` | Cleaned and enriched dataset (added Order Year, Order Month, Shipping Delay, Profit Margin) |
| `Superstore_Dashboard.pbix` | Power BI project file |
| `Dashboard_Export.pdf` / `.png` | Exported view of the final dashboard |
| `BI_Overview_Report.docx` | Business Intelligence overview report |
| `Executive_Summary_Report.docx` | Executive summary with insights, risks, opportunities, and recommendations |

## Dashboard Overview

**KPIs:** Total Sales, Total Profit, Total Orders, Average Sale, Profit Margin
**Visuals:** Bar charts, column charts, line chart (sales trend), donut chart (sales by region), map (sales by state), matrix (region × category), plus slicers for Region, Order Year, and Segment.

## Key Business Insights

- Technology is the most profitable category; Furniture drags down overall margin
- West and East regions generate over two-thirds of total company profit
- Consumer segment drives 50% of revenue and the largest share of profit
- Tables and Bookcases are structurally unprofitable despite steady sales volume
- Higher discount levels are linked to lower profit across the business

## Business Risks

- Texas posts a loss despite strong sales — a regional pricing/discounting problem
- Deep discounting is quietly eroding margin even as headline sales look healthy
- Over 85% of profit comes from just two categories — Technology and Office Supplies

## Business Opportunities

- Copiers has the highest profit margin (37%) but is under-scaled — room to grow
- The West region's approach can likely be replicated in the underperforming Central region
- Fixing pricing on Tables and Bookcases alone could recover over $21K in lost profit

## Recommendations

1. Cap discounting on Tables, Bookcases, and other loss-making sub-categories
2. Investigate and correct pricing/cost issues in the Central region and Texas
3. Reallocate marketing and inventory investment toward Technology and Copiers
4. Introduce a discount approval threshold or governance policy
5. Design retention and loyalty offers targeted at the Consumer segment

## Skills Developed

- Data cleaning and transformation with Power Query
- DAX measures (KPIs, ranking logic, conditional formatting)
- Interactive dashboard design for executive audiences
- Business insight generation and recommendation writing

---
*Part of the AnalystLab Africa Data Analytics Internship Programme — #AnalystLabAfrica*
