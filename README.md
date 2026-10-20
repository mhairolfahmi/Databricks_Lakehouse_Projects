# Databricks Lakehouse Projects

## Objective
This project builds a data pipeline for e-commerce to turn raw operational data
into actionable business insights. Data from CRM and ERP systems, covering
customers, products, and sales orders from December 2010 to January 2014, is
processed through Bronze, Silver, and Gold layers in a Databricks lakehouse.

## Approach
The pipeline follows the Medallion Architecture:
- **Bronze:** raw CSV files are ingested as-is into Delta tables.
- **Silver:** data is cleaned, standardized, and joined (customers, products,
  locations, and sales details).
- **Gold:** business-ready tables are created for reporting and visualization.

## Tools
Databricks, PySpark, SQL, Delta Lake, Power BI, Claude and GitHub for version control.

## Data Flow
<img width="781" height="502" alt="image" src="https://github.com/user-attachments/assets/30d8da1c-09b9-4a00-92e6-a978e2db75b9" />


## Final Dashboard
<img width="1320" height="724" alt="image" src="https://github.com/user-attachments/assets/de0ff5ee-d640-4872-bef6-4479346ca684" />

## Insight

### Monthly Trends
- Monthly sales have grew strongly year over year where the sales performance have accelerated sharply starting from early 2013.
- The number of total orders have growth slowly from 144 in Jan 2011 to 355 in Dec 2012, before it rose sharply to 632 in Jan 2013 and further growth throghout 2013 period.
- Average Order Values has declined gradually year over year.
- This indicates that the company’s sales growth has shifted from a few high-value orders to a larger number of lower-value orders
  
### Product Performance
- Bike contribute more than 90% of overall sales for the company, while accessories lead in total orders.
- The higher average price of bike contribute to its higher sales compared to others product.
- Australia and the United States are the top two markets for our company’s bikes by market share.
- The sales surge in 2013 was primarily driven by the United States, which recorded the highest sales for most months throughout the year.
- The Mountain-200 is the leading contributor to sales, with all five of the top-selling bikes being variants of this product line.
