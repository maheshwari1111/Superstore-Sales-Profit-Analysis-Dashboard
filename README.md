# Superstore Sales & Profit Analysis Dashboard — Power BI

An interactive Power BI dashboard analyzing **9,994+ retail transactions** across sales, profit, and fulfillment metrics, built to surface actionable business insights for a fictional retail superstore.

## Overview

This project transforms raw retail transaction data into a decision-ready dashboard. It covers sales performance, profitability, regional trends, and product-category breakdowns, enabling faster identification of high-performing regions, products, and profit trends.

## Dataset

- **Source:** Superstore Sales dataset (retail transactions)
- **Size:** 9,994+ records
- **Fields:** Order ID, Order Date, Ship Date, Ship Mode, Customer, Segment, Region, State, City, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit

## Key Features

- **Dynamic KPI Cards** — real-time totals for Sales, Profit, Quantity, and Orders
- **Trend Charts** — month-wise and year-over-year sales and profit trends
- **Geo-Map Visualization** — regional performance plotted across locations
- **Category Donut Chart** — sales/profit share by product category and sub-category
- **Interactive Slicers** — filter by month, region, category, and segment for real-time analysis
- **Category-Wise Breakdowns** — drill-down view of performance by product category

## Tools & Technologies

- **Power BI Desktop** — data modeling, DAX measures, and dashboard design
- **Power Query** — data cleaning and transformation
- **DAX** — calculated measures for KPIs (Total Sales, Total Profit, Profit Margin, etc.)

## Key Insights

- Identified top-performing regions and product categories by profit margin
- Surfaced underperforming sub-categories with high discounting and negative profit
- Enabled month-wise trend tracking to spot seasonal sales patterns

## Dashboard Preview

*(Add a screenshot or GIF of your dashboard here, e.g. `![Dashboard Preview](assets/dashboard-preview.png)`)*

## Repository Structure

```
├── data/
│   └── superstore_dataset.csv       # Raw dataset (or link to source)
├── superstore_dashboard.pbix        # Power BI dashboard file
├── assets/
│   └── dashboard-preview.png        # Dashboard screenshot(s)
└── README.md
```

## How to Use

1. Clone this repository
2. Open `superstore_dashboard.pbix` in Power BI Desktop
3. Refresh the data source if needed (`Home > Refresh`)
4. Explore the dashboard using the slicers and filters

## Author

**Maheshwari Vinod Mutkure**
B.Tech, Artificial Intelligence & Data Science
[LinkedIn](https://linkedin.com/in/maheshwarimutkure) | [GitHub](https://github.com/maheshwari1111)
