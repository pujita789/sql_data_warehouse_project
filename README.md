# sql_data_warehouse_project
This is a Retail sales data warehouse pipeline.
# Details
A scalable Medallion Architecture-based data warehouse built using Python, SQL, Airflow, Snowflake, and dbt for retail sales analytics.
---what problem i have solved?
# Problem Statement
An AI-Driven e-commerce company recives millions of customer interactions , orders , product views and transactional events from multiple platforms such as web applications , mobile applications CSV exports , and third-party systems.

The data was highly fragmented, inconsistent, and difficult to analyze in real time. Analysts and ML teams faced challenges in:
- Tracking customer purchase behavior
- Understanding product performance
- Building recommendation systems
- Generating reliable KPI reports
- Creating personalized customer experiences

Because the raw data existed across disconnected systems, reporting pipelines were slow, data quality was inconsistent, and AI models lacked clean historical datasets for training.

-----why the warehouse was needed 
This project solves the problem by building a scalable cloud-based Medallion Architecture Data Warehouse that:
- Centralizes customer, product, and order data
- Cleans and transforms raw transactional records
- Creates analytics-ready datasets
- Enables faster business intelligence reporting
- Supports AI/ML use cases such as recommendation systems, customer segmentation, demand forecasting, and personalized shopping experiences

The platform is designed to serve as a single source of truth for both analytics and AI-driven decision-making.
---Design
# AI-Ready Medallion Data Warehouse Architecture
