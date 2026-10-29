# Customer Retention & Churn Analytics for E-Commerce

## Project Overview

This project analyzes customer purchasing behavior, repeat purchases, customer segments, and inactivity risk using the Brazilian E-Commerce Public Dataset by Olist.

The goal is to turn historical e-commerce transaction data into actionable insights that can support customer retention strategies and improve repeat-purchase opportunities.

## Business Objectives

- Measure customer retention and repeat-purchase behavior.
- Identify customers who may be inactive based on a defined inactivity rule.
- Segment customers using Recency, Frequency, and Monetary (RFM) analysis.
- Analyze historical payment value and customer purchasing patterns.
- Recommend data-driven customer engagement strategies.

## Key Findings

| Metric | Result |
|---|---:|
| Delivered customers analyzed | 93,358 |
| Inactivity candidates | 66,062 |
| Repeat customer rate | 3.00% |
| Historical payment value | R$15.42 million |

**Important:** Inactivity candidates are customers who meet the project's inactivity criteria; they are not confirmed permanently churned customers. Historical payment value represents past payment activity, not lost revenue.

## Customer Segmentation

The analysis groups customers into behavioral segments, including:

- High Spenders
- Hibernating One-Time Buyers
- Recent One-Time Buyers
- Needs Nurturing
- At Risk – Repeat Buyers
- Champions
- Loyal Customers

These segments can help prioritize customer engagement and retention activities.

## Tools & Technologies

- **Python:** Data processing and analysis
- **Pandas:** Data cleaning and transformation
- **MySQL and SQL:** Data querying, aggregation, and analysis
- **Power BI Desktop:** Interactive dashboard development
- **DAX:** KPI calculations and measures
- **GitHub Pages:** Project website hosting

## Project Workflow

1. Loaded and inspected the Olist e-commerce datasets.
2. Audited customers, orders, delivery status, and missing timestamps.
3. Defined customer eligibility and inactivity rules.
4. Calculated customer-level RFM metrics.
5. Created customer segments using business rules.
6. Queried and summarized results using MySQL and SQL.
7. Built KPI measures and visualizations in Power BI.
8. Developed business recommendations based on the findings.

## Business Recommendations

- Test targeted re-engagement campaigns for eligible inactive customers.
- Encourage second purchases among one-time buyers.
- Personalize offers based on customer value and purchasing history.
- Monitor repeat-purchase rate and customer segment movement over time.
- Evaluate campaign outcomes before expanding retention initiatives.

## Power BI Dashboard

The dashboard presents customer KPIs, inactivity candidates, historical payment value, and customer segment insights.

View the dashboard screenshot on the [project website](https://Kiran29291.github.io/customer-retention-churn-analytics/).

## Dataset

Source: [Brazilian E-Commerce Public Dataset by Olist on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

The dataset contains historical Brazilian e-commerce orders and related customer, payment, and order-item information. Refer to the original dataset page for source details and licensing information.

## Project Links

- **Live Website:** https://Kiran29291.github.io/customer-retention-churn-analytics/
- **GitHub Repository:** https://github.com/Kiran29291/customer-retention-churn-analytics

## Limitations

- The analysis is based on historical data and does not prove that an inactive customer has permanently churned.
- Inactivity classifications depend on the defined reference date and eligibility rules.
- Recommendations are hypotheses to test; their actual impact requires measurement through future campaigns.

## Author

Yendluri Kiran Kumar |Data Analytics Portfolio Project

**Skills demonstrated:** Python, Pandas, MySQL, SQL, Power BI, DAX, data analysis, customer segmentation, and business insight communication.
