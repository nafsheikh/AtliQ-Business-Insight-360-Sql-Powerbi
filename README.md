# AtliQ-Business-Insight-360-Sql-Powerbi

## Overview

**AtliQ Hardware**, a rapidly growing company specializing in computers and accessories, experienced unexpected losses after expanding into the American market. To address this challenge and gain a competitive advantage, the company adopted Power BI to enable advanced analytics and data-driven decision-making

This project presents a comprehensive business intelligence solution that provides actionable insights across key business functions:

💰 Finance

📈 Sales

📢 Marketing

🚚 Supply Chain

💼 Executive

The dashboard empowers stakeholders to monitor performance, identify trends, and make informed strategic decisions

This project was completed as part of the **Codebasics Power BI Course**, which provided comprehensive guidance and practical insights into building analytics solutions.

## Objectives

This project aims to build a scalable and insight-driven analytics solution to support strategic business decisions.
Key objectives include:

1. Empower stakeholders with data-driven decision-making across finance, sales, marketing, and supply chain domains. 

2. Utilize Power BI’s advanced visualization capabilities to transform raw data into actionable insights

3. Design and implement a robust, optimized data model for high performance and scalability

4. Enable forecast vs actual analysis to improve demand planning and operational efficiency

---

## Datasets

### **gdb041**— Core Business Data
- **dim_customer**: Contains master customer data required for customer-level analysis.
- **dim_market**: Provides information about market segments and geographic distribution.
- **dim_product**: Includes detailed product master data for product-level reporting.
- **fact_forecast_monthly**: Stores monthly demand forecasts to support warehouse planning and cost optimization.
- **fact_sales_monthly**: Captures actual monthly sales quantities for variance analysis against forecasts.

### **gdb056**— Financial & Cost Data
- **freight_cost**: Contains logistics and freight-related expenses.
- **gross_price**: Provides gross pricing details used in revenue calculations.
- **manufacturing_cost**: Stores product manufacturing costs for margin analysis.
- **pre_invoice_deductions**: Records discounts applied before invoicing.
- **post_invoice_deductions**: Records rebates and adjustments applied after invoicing.

---

## Data Processing Workflow

1. **Data Extraction**: Data imported from MySQL into Power BI.
2. **Data Cleaning**: Handled missing values, Removed inconsistencies, Standardized fields to ensure high data quality.
3. **Data Modeling**: Designed an optimized Snowflake schema, Established relationships between fact and dimension tables                              Improved overall model performance.
4. **Data Analysis**: Built calculated columns, Created DAX measures,Developed interactive dashboards for actionable insights.


### Importance of Data Modeling

Data modeling is the foundation of any effective Power BI solution. A well-designed model:

1. Improves report performance and scalability
2. Ensures accurate and consistent calculations
3. Simplifies complex analysis
4. Enhances dashboard user experience

Without proper data modeling, reports can become slow, difficult to maintain, and prone to calculation errors. A strong semantic model enables reliable, efficient, and business-ready analytics
![Data Modelling]


