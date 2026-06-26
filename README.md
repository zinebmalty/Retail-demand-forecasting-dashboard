# Retail-demand-forecasting-dashboard
Power BI dashboard for retail sales analysis and 3-month demand forecasting using DAX and Power Query.

Project Overview

This project presents an end-to-end retail demand forecasting solution built with Power BI. It analyzes historical sales data, identifies demand trends, and forecasts future demand for the next three months to support inventory planning and business decision-making.

⸻

Business Objectives

The main objectives of this project are to:

* Analyze historical retail sales performance.
* Monitor revenue and demand trends over time.
* Identify the best-performing product formats and categories.
* Compare sales performance across cities.
* Forecast customer demand for the next three months.
* Support inventory planning and reduce stock shortages or overstock situations.

⸻

Prepare

Data Source

Retail sales dataset containing:

* Sales transactions
* Product categories
* Store information
* Calendar (Date table)

Data Preparation

The dataset was prepared using Power Query by:

* Removing duplicate records.
* Handling missing values.
* Correcting data types.
* Creating a Calendar table.
* Building relationships between tables.
* Optimizing the data model.

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

* Measuring overall business performance using Total Revenue, Total Quantity, YoY Revenue Growth, and Total Forecast Demand.
* Monitoring revenue trends over time to identify seasonality, growth periods, and unusual demand spikes.
* Forecasting demand for the next three months using Power BI’s built-in forecasting capabilities.
* Comparing revenue performance across different cities.
* Identifying the highest-demand product categories.
* Ranking product formats based on total demand.
* Evaluating yearly performance using an interactive Year slicer.
* Measuring Year-over-Year revenue growth to assess business performance over time.

⸻

Dashboard Preview


⸻

Business Insights

The dashboard revealed several important insights:

* Revenue increased significantly during 2024.
* Demand shows a clear upward trend toward the end of the analysis period.
* A small number of product categories generate the majority of sales volume.
* Product demand varies considerably across cities.
* Certain product formats consistently outperform others.
* Demand forecasting indicates continued growth over the next three months.

⸻
 Business Recommendations

Based on the analysis, the following actions are recommended:

* Increase inventory before forecasted demand peaks to reduce stockout risk.
* Prioritize replenishment for the highest-demand product categories and formats.
* Allocate more inventory to cities with consistently strong demand.
* Investigate underperforming cities to identify operational or marketing improvement opportunities.
* Use demand forecasts to improve purchasing schedules and warehouse planning.
* Continuously monitor YoY Revenue Growth to evaluate business performance.
* Compare forecasted demand with actual demand regularly to improve forecasting accuracy.
* Use the dashboard as an executive decision-support tool for sales planning, inventory management, and supply chain optimization.

⸻
Project Outcome

This dashboard enables decision-makers to monitor sales performance, evaluate historical trends, and forecast future demand to support more informed inventory and supply chain decisions.
