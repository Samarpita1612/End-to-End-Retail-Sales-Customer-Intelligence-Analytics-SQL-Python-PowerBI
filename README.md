# End-to-End Retail Sales & Customer Intelligence Analytics  
### SQL • Python • Power BI

## Project Overview

This project presents an **end-to-end retail analytics pipeline**, transforming raw transactional data into actionable business insights.

The objective was to simulate a real-world business scenario where leadership requires data-driven insights to improve profitability, optimize discount strategy, and strengthen customer retention.

The project covers the complete lifecycle:

Data Collection → Data Modeling → SQL Analysis → Advanced Python Segmentation → Business Intelligence Dashboard → Strategic Recommendations

---

## Dataset

- Source: Public Superstore Retail Dataset (Kaggle)
- Total Records: 9,694 transactions
- Total Orders: 4,931
- Total Customers: 793
- Total Revenue Analyzed: $2.27M
- Time Span: Multi-year transactional retail data

Key attributes include:
- Sales
- Profit
- Discount
- Region
- Product Category
- Customer Information
- Order & Shipping Dates

---

## Tools & Technologies Used

**Database Layer**
- MySQL
- SQL (Data modeling, KPI queries, loss analysis, aggregations)

**Analytics Layer**
- Python
- Pandas
- NumPy
- SQLAlchemy (Database connection)

**Business Intelligence Layer**
- Power BI Desktop
- DAX (Calculated measures & KPIs)

**Workflow Architecture**

CSV → MySQL → SQL Analysis → Python (RFM Segmentation) → MySQL → Power BI Dashboard

This structure ensures a fully reproducible and scalable end-to-end analytical workflow.

---

## Data Modeling (SQL)

- Designed relational schema
- Structured transactional retail table
- Created analytical views for reporting
- Performed KPI and profitability analysis

Core SQL Analyses Included:
- Revenue & Profit Computation
- Regional Performance Analysis
- Category Profitability
- Loss-Making Order Identification
- Discount Impact Analysis
- Revenue Concentration Study

---

## Financial Performance Insights

- Total Revenue: $2,272,450
- Total Profit: $282,858
- Profit Margin: 12.45%
- Loss-Making Orders: 36% of transactions
- Total Loss from Negative Orders: $154,511

Key Finding:
Eliminating loss-heavy transactions could increase profitability by approximately 35%.

---

## Discount Impact Analysis

Discount behavior analysis revealed:

- Discounts above 20% lead to negative average profitability
- 50% discount results in approximately $310 average loss per order
- Aggressive discounting is the primary contributor to margin erosion

Business Implication:
The current discount strategy significantly impacts profit sustainability.

---

## Regional & Category Performance

Regional Insights:
- West region generates the highest revenue contribution
- South region underperforms relative to peers

Category Insights:
- Technology is the most profitable category
- Furniture generates the highest financial loss impact
- Office Supplies maintains stable performance

Implication:
Furniture pricing and discount policies require strategic revision.

---

## Customer Intelligence (Python – RFM Segmentation)

Performed Recency-Frequency-Monetary (RFM) analysis on 793 customers.

Customer Segmentation Results:

- Champions: 7%
- Loyal Customers: 15%
- Recent Customers: 12%
- At Risk: 21%
- Others: Remaining segment

Revenue Concentration:

- Top 10% of customers contribute 31% of total revenue
- Loyal customers (15%) generate 22% of total revenue
- Champions (7%) contribute 12%

Business Insight:
A structured retention and upsell strategy can significantly improve lifetime value and reduce churn risk.

---

## Power BI Executive Dashboard

A 4-page interactive dashboard was developed:

1. Executive Overview
2. Product & Profitability Analysis
3. Discount & Loss Impact Analysis
4. Customer Intelligence & Segmentation

The dashboard enables stakeholders to:
- Monitor margin trends
- Identify loss drivers
- Evaluate discount strategy effectiveness
- Track customer segment performance

---

## Strategic Recommendations

1. Implement a maximum discount cap of 20%.
2. Re-evaluate pricing structure for Furniture category.
3. Launch targeted retention campaigns for At-Risk customers.
4. Develop loyalty incentives for Champions and Loyal segments.
5. Expand performance in underperforming regions.

---

## Business Impact Potential

By optimizing discount policy and reducing loss-making orders:

- Potential profit recovery: $150K+
- Estimated margin improvement: 4–6%
- Improved customer lifetime value through segmentation strategy

---

## Repository Structure
Retail-Sales-Analytics/
│
├── SQL/
│ ├── schema.sql
│ ├── analysis_queries.sql
│
├── Python/
│ ├── rfm_analysis.ipynb
│
├── PowerBI/
│ ├── retail_dashboard.pbix
│
├── data/
│ ├── superstore_sales.csv
│
├── project_report.md
└── README.md

---

## Key Competencies Demonstrated

- End-to-End Data Pipeline Design
- SQL Data Modeling & Business Querying
- Loss & Margin Analysis
- Discount Optimization Modeling
- Customer Segmentation (RFM)
- Business Intelligence Dashboard Development
- Executive-Level Business Interpretation

---

## Conclusion

This project demonstrates a complete end-to-end analytics workflow, from raw transactional data to executive-level business recommendations.

It reflects practical skills required in real-world data analyst roles, including data modeling, financial performance analysis, customer intelligence, and strategic decision support.
