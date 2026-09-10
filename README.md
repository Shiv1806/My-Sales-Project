# Pizza Sales Analysis & Power BI Dashboard

A data analysis project combining SQL Server analysis with Power BI reporting to explore pizza sales performance, customer demand, product mix and sales trends.

## Project Overview

This project analyses a pizza sales dataset containing 48,360 records. The analysis uses SQL to calculate key sales and order metrics, explore trends and compare pizza categories, sizes and individual products. The results are presented through an interactive Power BI dashboard.

## Key Analysis Areas

- Total revenue and order performance
- Average order value and average pizzas per order
- Daily and monthly order/revenue trends
- Sales by pizza category
- Sales by pizza size
- Best- and worst-performing pizzas
- Product mix and contribution to overall sales

## Tools & Technologies

- SQL Server / SQL
- Power BI
- Microsoft Excel
- CSV data

## Repository Structure

```text
Pizza-Sales-Portfolio/
├── data/
│   ├── pizza_sales.csv
│   └── pizza_sales.xlsx
├── docs/
│   ├── Pizza-Sales-Analytics.md
│   └── Pizza-Sales-SQL-Queries-Results.docx
├── powerbi/
│   └── Data-Warehouse-Pizza-Sales.pbix
│   └── screenshots
├── sql/
│   └── pizza-sales-analysis.sql
└── README.md
```

## Dashboard

The Power BI report provides interactive views of sales performance, trends, category and size performance, and individual pizza performance.

### Dashboard Preview

**Overview - sales KPIs, order trends, category and size performance**

(powerbi/screenshots/Dashboard 1.png)

**Product Analysis - top pizzas, sales by size and least-ordered pizzas**

![Pizza Sales Product Analysis](powerbi/screenshots/dashboard2.png)

The original Power BI file is available in `powerbi/`, with dashboard screenshots in `powerbi/screenshots/`. 

## SQL Analysis

The SQL script contains the analysis queries used to calculate KPIs and investigate sales trends and product performance. SQL queries results are available under docs.

## Notes

This repository contains the original project artefacts supplied for the Pizza Sales analysis. The README is a summary of the work.
