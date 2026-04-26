#  Global Pharma Sales Intelligence Dashboard (Power BI)
End-to-end Business Intelligence solution delivering actionable insights on global pharmaceutical sales, product performance, and inventory risk using advanced DAX and data modeling.

## Dashboard Preview

A quick look at the interactive Power BI reports built for sales, product, regional, and inventory analysis.

---

### Executive Overview

Provides a high-level summary of key business KPIs such as Total Sales, Profit, YoY Growth, and overall performance trends.

![Executive Overview](https://github.com/Shishir-Kumar-Raj/global-pharma-sales-dashboard/blob/5300d5d8c627ef91150f60bf1a9816189bab092c/dashboard_screenshots/Executive%20Overview.png)

---

### Regional Sales Performance

Analyzes regional sales performance to identify high- and low-performing markets, enabling targeted growth strategies.

![Regional sales performance](https://github.com/Shishir-Kumar-Raj/global-pharma-sales-dashboard/blob/5300d5d8c627ef91150f60bf1a9816189bab092c/dashboard_screenshots/Regional%20Sales%20Performance.png)

---

### Country Analysis

Provides a country-level breakdown of sales performance, highlighting top-performing markets, revenue distribution, and growth trends across regions. Helps identify high-demand areas and opportunities for expansion.

![Country Analysis](https://github.com/Shishir-Kumar-Raj/global-pharma-sales-dashboard/blob/5300d5d8c627ef91150f60bf1a9816189bab092c/dashboard_screenshots/Country%20Analysis.png)

---

### Inventory & Expiry Risk Monitoring

Monitors stock availability and product expiry to flag low inventory and near-expiry risks, enabling proactive supply chain decisions and minimizing losses.

![Inventory & Expiry Risk Monitoring](https://github.com/Shishir-Kumar-Raj/global-pharma-sales-dashboard/blob/5300d5d8c627ef91150f60bf1a9816189bab092c/dashboard_screenshots/Invantory%20and%20risk%20Monitoring.png)

---

### Covid impact analysis

COVID-19 led to a noticeable surge in demand for immunity-boosting products such as vitamins and herbal supplements, resulting in a temporary spike in sales during the pandemic period.

![Covid impact analysis](https://github.com/Shishir-Kumar-Raj/global-pharma-sales-dashboard/blob/5300d5d8c627ef91150f60bf1a9816189bab092c/dashboard_screenshots/Covid%20impact%20Analysis.png)

---

### Demographic Insights

Analyzes customer segments by age group and gender to identify key contributors to sales and understand purchasing patterns across different demographics.

![Demographic Insights](https://github.com/Shishir-Kumar-Raj/global-pharma-sales-dashboard/blob/5300d5d8c627ef91150f60bf1a9816189bab092c/dashboard_screenshots/Demographic%20Insight.png)

## Project Overview
This project delivers an enterprise-style Power BI dashboard for Himalaya to analyze pharmaceutical sales, product performance, and inventory risk across global markets.  

It enables stakeholders to monitor revenue trends, identify top-performing products and regions, and make data-driven decisions through interactive visual analytics.

## Problem
No centralized system to monitor sales, product performance, and inventory across regions.

## Key Features
- 5 interactive dashboard pages  
- 20+ DAX measures (YoY Growth, Market Share, Moving Avg)  
- Star Schema data model  
- Power Query ETL pipeline  
- Interactive filters and drill-downs

## Key Insights

- Chronic care products contribute the largest share of total revenue, indicating strong recurring demand in long-term treatments  
- South Asia leads in sales volume, while North America and Europe generate higher revenue per unit, highlighting pricing differences across regions  
- COVID-19 period shows a noticeable spike in demand for immunity and vitamin-based products  
- A small group of top-performing products contributes a significant percentage of total revenue (Pareto effect)  
- Certain regions show consistent low stock levels, indicating potential supply chain inefficiencies and risk of stockouts  
- Products nearing expiry with unsold inventory highlight the need for better demand forecasting and inventory planning  
- The age group 26–45 contributes the highest share of total sales, making it the primary target customer segment

## Tech Stack

| Category        | Tools / Technologies |
|----------------|---------------------|
| BI Tool        | Power BI Desktop |
| Data Modeling  | Star Schema |
| Data Processing| Power Query (M) |
| Calculations   | DAX |
| Data Source    | CSV |
| Optional       | SQL |

## Project Structure

```
Global Pharma Sales Intelligence Dashboard (Power BI)/
│
├── Global_Pharma_Sales_Dashboard.pbix   
├── README.md                              
│
├── data/                                  
│   └── global_pharma_sales_data.csv
│
├── dashboard_screenshots/                           
│   ├── Executive Overview.png
│   ├── Regional Sales Performance.png
│   ├── Country Analysis.png
│   ├── Inventory & Expiry Risk Monitoring.png
│   ├── Covid impact analysis.png
│   └── Demographic Insights.png
│ 
├── docs/ 
│   └── Global_Pharma_Sales_Dashboard_Documentation.pdf
```
## Star Schema
This project uses a Star Schema data model with a central Fact table connected to multiple Dimension tables for optimized performance and scalability.

![Star Schema](https://github.com/Shishir-Kumar-Raj/global-pharma-sales-dashboard/blob/774594c174fd4afb58d3217ab3608ec66cbd7680/dashboard_screenshots/Star%20Schema.png)

## Documentation

-  [Project Summary (Quick Read)](https://github.com/Shishir-Kumar-Raj/global-pharma-sales-dashboard/blob/fd3e5db555057230d8b4cd150557546d8e3007c1/Document/Global_Pharma_Sales_Dashboard_Documentation.pdf)  

> Summary is recommended for quick understanding.

> Note: This project uses simulated pharmaceutical data for demonstration purposes.

