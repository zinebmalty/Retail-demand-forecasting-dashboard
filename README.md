# Retail-demand-forecasting-dashboard
Power BI dashboard for retail sales analysis and 3-month demand forecasting using DAX and Power Query.

Project Overview

This project presents an end-to-end retail demand forecasting solution built with Power BI.

⸻

Business Objectives

The main objectives of this project are to:

* Analyze historical retail sales performance.
* Monitor sales trends over time.
* Compare sales performance across cities and different store locations
* Forecast customer demand for the next three months.


⸻

Data Preparation

The dataset was prepared using Power Query by:

* Removing duplicate records.
* Handling missing values.
* Correcting data types.
* Outliers & High-Value Items Retention: Preserved extreme unit prices (up to $28,999.90) and return records (negative quantities) following data integrity validation, providing full transaction completeness without artificial filtering.
* Creating a Calendar table.
* Building relationships between tables.



⸻

Process

Data modeling followed a Star Schema approach.

Measures were created using DAX, including:

* Total Revenue
* Total Quantity
* Average Price
* YoY Revenue Growth
* Total Forecast Demand

Time intelligence functions used:

* SAMEPERIODLASTYEAR()
* DATEADD()
* DIVIDE()
* CALCULATE()

Power BI Forecasting was applied to generate demand predictions for the next three months.

⸻

Analyze

The analysis focused on:

* Measuring overall business performance using Total Sales , Total Quantity, and Total Forecast Demand.
* Monitoring sales trends over time to identify seasonality, growth periods, and unusual demand spikes.
* Forecasting demand for the next three months using Power BI’s built-in forecasting capabilities.
* Comparing sales performance across different cities and stores
* The sale trend covers the available period from August 2022 to September 2024. Since 2022 and 2024 are partial years, I use the trend to show revenue patterns over time rather than to compare complete annual revenues.

⸻

Dashboard Preview

![Dashboard](Dashboard.png)

⸻

Business Insights

* **Total Sales Revenue:** Achieved **$5.7 Billion** in net revenue across **7.43 Million records**.
* **Total Volume Sold:** Reached **41.94 Million units** in overall sales volume.
* **Pricing Range Impact:** High-value inventory (unit prices scaling up to **$28,999.90**) heavily drives total portfolio performance.

The dashboard revealed several important insights:

* Sale increased significantly during 2024.
* Demand shows a clear upward trend toward the end of the analysis period.
* Product demand varies considerably across cities.
* Certain product formats consistently outperform others.
* Demand forecasting indicates continued growth over the next three months.

⸻
 Business Recommendations

Based on the analysis, the following actions are recommended:

* Increase inventory before forecasted demand peaks to reduce stockout risk.
* Prioritize replenishment for the highest-demand formats.
* Allocate more inventory to cities with consistently strong demand.
* Compare forecasted demand with actual demand regularly to improve forecasting accuracy.
* Use the dashboard as an executive decision-support tool for sales planning, inventory management, and supply chain optimization.

⸻
Project Outcome

This dashboard enables decision-makers to monitor sales performance, evaluate historical trends, and forecast future demand to support more informed inventory and supply chain decisions.
