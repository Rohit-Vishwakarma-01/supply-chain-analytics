# Power BI Dashboard

## Overview
This folder contains the Power BI report for the Supply Chain Analytics project. The report is designed to present key business metrics and insights related to sales, profitability, delivery performance, products, customers, and geographic performance.

The objective is to transform analyzed supply chain data into interactive dashboards that help users understand business performance and identify potential areas for improvement.

## Dashboard Objectives
- Monitor sales and profitability.
- Evaluate delivery performance and late-delivery patterns.
- Identify high-performing and low-performing products.
- Analyze the relationship between discounts and profitability.
- Compare performance across customers, markets, and regions.
- Present business insights through interactive visualizations.

## Planned Report Pages

### 1. Executive Overview
Provides a high-level summary of business performance using KPI cards, trend charts, and delivery indicators.

Potential metrics:
- Total Sales
- Total Profit
- Total Orders
- Profit Margin
- Late Delivery Rate

### 2. Sales and Profitability
Analyzes sales and profit trends over time and compares performance across product categories and markets.

Potential visuals:
- Sales and profit trends
- Sales by product category
- Profit by category or market
- Discount and profitability analysis

### 3. Delivery and Logistics
Examines delivery performance and helps identify patterns associated with late deliveries.

Potential visuals:
- Late deliveries versus on-time deliveries
- Delivery performance by shipping mode
- Actual versus scheduled shipping time
- Delivery performance by region


## Key Performance Indicators (KPIs)
The report may include the following KPIs, subject to data validation:

| KPI | Description |
|---|---|
| Total Sales | Total sales value for the selected data and filters |
| Total Profit | Total profit based on the validated profit measure |
| Profit Margin | Profit divided by the corresponding sales value |
| Total Orders | Count of distinct orders |
| Average Order Value | Sales divided by distinct orders, using a consistent calculation level |
| Late Delivery Rate | Late-delivery orders divided by eligible distinct orders |
| Average Delivery Delay | Average difference between actual and scheduled shipping duration, where the required fields are available |

KPI formulas and aggregation levels will be validated to avoid double-counting order-level values across multiple order-item records.

## Interactivity
The report is intended to support interactive analysis through appropriate slicers, cross-filtering, drill-through, and tooltips where useful.

Potential slicers include:
- Order Date
- Market or Region
- Product Category
- Customer Segment
- Shipping Mode
- Delivery Status

The final interactions will depend on the completed report and available fields.

## How to Open the Report
1. Install Microsoft Power BI Desktop.
2. Download or clone this GitHub repository.
3. Open the `.pbix` report file from this folder, once it is available.
4. If prompted, update the data source path to match your local dataset location.
5. Refresh the data if the required source files are available.
6. Use the slicers and visuals to explore the analysis.

## Report Screenshots
Dashboard screenshots can be added to the project's `images/` folder and displayed here.

Example:


![Executive Dashboard](images/Overview.png)

![Sales and Profitability](images/Sales&Profitability.png)

![Delivery and Logistics](images/Delivery&Logistic.png)


Replace these example paths with the actual screenshot filenames.

## Data and Refresh Notes
- The report depends on the dataset and data model used during development.
- Local data source paths may need to be updated when the project is opened on another computer.
- Measures and visuals should be validated after refreshing the data.
- Do not publish sensitive customer information or confidential data in report files or screenshots.

## Current Status
**Status:** Dashboard development in completed.


## Related Project Files
- Main project documentation: `../README.md`
- Python notebooks: `../notebooks/`
- Dataset instructions: `../data/README.md`
- Python dependencies: `../requirements.txt`

## Author
**Rohit Vishwakarma**

Aspiring Data Analyst | Python | SQL | Power BI | Excel | Data Visualization
