# Loan Portfolio Analysis Dashboard

This project presents a business intelligence dashboard analyzing a loan portfolio using Bigquery and Looker.

The goal of the dashboard is to provide insights into the current state of outstanding loans, identify risk patterns, and highlight high-value customers.

## Data Preparation with BigQuery

Before building the dashboard in Looker, SQL queries were executed in BigQuery to explore and prepare the dataset.

Some tasks included:

• Creating tables with aggregated loan metrics  
• Extracting distinct loan purposes  
• Calculating the number of loans issued per year  
• Exploring nested fields in the dataset

Below are examples of SQL queries executed during the analysis.

![BigQuery Query](images/bigquery_query_1.png)
![BigQuery Query](images/bigquery_query_2.png)
![BigQuery Query](images/bigquery_query_3.png)

## Dashboard Preview

![Dashboard](dashboard.png)

## Tools Used

- Google Cloud Platform
- Looker
- SQL
- Data Visualization

## Key Metrics

The dashboard includes:

• Total Outstanding Loan Balance  
• Distribution of loans by status  
• Geographic concentration of loans by state  
• Top customers by annual income

## Insights

From this analysis, we can observe:

• The majority of loans are currently active and in good standing  
• A smaller portion of the portfolio shows risk through late payments or charge-offs  
• Some states concentrate a higher number of outstanding loans, which may require additional monitoring  
• High-income customers represent a valuable segment with active loans

## Purpose

This dashboard demonstrates how business intelligence tools can be used to monitor loan portfolios, identify risk signals, and support data-driven decision making.
