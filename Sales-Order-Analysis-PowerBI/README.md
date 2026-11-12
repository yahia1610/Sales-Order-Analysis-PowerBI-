# Sales & Order Analysis Dashboard | Power BI

## Project Overview

An interactive **Sales & Order Analysis Dashboard** developed using Microsoft Power BI to analyze order performance, sales metrics, product demand, order statuses, and geographical distribution.

The project transforms raw transactional data into meaningful business insights through interactive visualizations, KPI tracking, and structured data modeling.

The dashboard consists of **three analytical pages**, providing different perspectives on sales and order performance.

## Business Objectives

- Monitor overall sales and order performance.
- Analyze order trends over time.
- Identify the most frequently ordered product subcategories.
- Evaluate order distribution across different statuses.
- Compare order volume and financial performance across territories.
- Provide insights to support data-driven business decisions.

## Tools & Technologies

- **Microsoft Power BI** – Dashboard development and visualization.
- **Power Query** – Data transformation and preparation.
- **DAX (Data Analysis Expressions)** – KPI calculations and measures.
- **Data Modeling** – Relational data modeling using Fact and Dimension tables.

## Data Model

The project uses a structured **Star Schema** data model to organize transactional data and analytical dimensions.

### Fact Table
- `Fact_table`

Contains transactional information, including:
- Order ID and Order Detail ID
- Customer ID
- Product ID
- Order Date
- Order Quantity
- Freight
- Line Total
- Online Order Flag

### Dimension Tables

- `Dim_date` – Order date information.
- `Dim_product` – Product, category, and subcategory details.
- `Dim_ShipMethod` – Shipping method information.
- `Dim_status` – Order status classifications.
- `Dim_territory` – Geographical territory information.

### Measures Table
- `DAX Measures table` – Centralized location for analytical DAX measures.

## Key Performance Indicators (KPIs)

The main dashboard displays the following metrics:

| KPI | Value |
|---|---:|
| Order Details | 24K |
| Total Orders | 1,465 |
| Total Due | 33.93M |
| Total Freight | 915.97K |
| Total Subtotal | 30.31M |
| Total Tax | 2.93M |

## Dashboard Pages & Visualizations

### Page 1 – Sales & Order Overview

Provides a comprehensive overview of business performance through six KPI cards and four visualizations.

**Key Visualizations:**

1. **Orders by Order Date**
   - Area chart showing order volume trends over time.
   - Helps identify changes and patterns in ordering activity.

2. **Orders by Product Subcategory**
   - Horizontal bar chart ranking product subcategories by order quantity.
   - Highlights the most frequently ordered products.

3. **Orders by Status**
   - Doughnut chart showing the distribution of orders across different statuses:
     - Approved
     - In Process
     - Shipped
     - Cancelled
     - Rejected
     - Backordered

4. **Orders and Total Due by Territory**
   - Clustered column chart comparing order counts and total due across geographical territories.

### Page 2 – Financial Analysis by Territory

**Total Due by Territory**

- Pie chart illustrating the contribution of each territory to total due.
- Compares the financial distribution across different geographical regions.
- Helps identify territories with higher financial contributions.

### Page 3 – Order Status Analysis

**Orders by Status**

- Horizontal bar chart displaying the number of orders for each status.
- Helps monitor order processing and fulfillment.
- Provides a clearer comparison of order status volumes.

## Key Features

- Three analytical dashboard pages.
- KPI cards for financial and operational monitoring.
- Interactive data visualizations.
- Time-based order trend analysis.
- Product subcategory performance analysis.
- Order status distribution and comparison.
- Geographical and territory-based analysis.
- Star Schema data modeling.
- Centralized DAX measures.

## Business Value

The dashboard supports business stakeholders in:

- Monitoring sales and order performance.
- Identifying high-demand product subcategories.
- Understanding order processing and fulfillment patterns.
- Evaluating geographical performance.
- Monitoring financial indicators.
- Making informed, data-driven business decisions.

## Project Structure

```text
Sales-Order-Analysis-PowerBI/
│
├── README.md
├── Sales_Order_Dashboard.pbix
│
└── images/
    ├── dashboard-overview.png
    ├── financial-analysis.png
    ├── order-status-analysis.png
    └── data-model.png
```

## Author

**Yahia Eid**

Data Science | Machine Learning | Data Analytics

