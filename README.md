
1. Project Title / Headline
 Car Sales Analytics Dashboard | Power BI + SQL Interactive Report
A comprehensive analytics solution combining SQL-based data extraction and Power BI visualization to track automotive sales performance across regions, dealers, and car models—providing actionable insights into revenue, trends, and growth metrics.

2. Short Description / Purpose

The Car Sales Dashboard integrates SQL and Power BI to analyze company-wide car sales, dealer efficiency, and customer preferences. It enables managers and analysts to monitor YTD/MTD sales, average price, and total cars sold, driving data-driven decisions in sales, inventory, and marketing strategies.

3. Tech Stack

This project was developed using the following tools and technologies:
• SQL Server – For data extraction, joins, aggregations, and transformation logic.
• Power BI Desktop – For building interactive dashboards and visuals.
• Power Query (M) – For ETL (Extract, Transform, Load) operations.
• DAX (Data Analysis Expressions) – For calculated KPIs like YTD/MTD Sales, Growth %, and Avg. Price.
• Data Modeling – Star schema with fact and dimension tables for performance optimization.
• Power BI Service – For publishing, sharing, and scheduled refresh.
• File Format: .sql for queries, .pbix for dashboard, .png for portfolio preview.

4. Data Source

Source: SQL-based car sales database (sample automotive dataset).
Tables used:

CarSalesFact – Transactional data (sales, quantity, amount, dealer).

DealerDim – Dealer and regional details.

CarDim – Vehicle details (model, color, engine, transmission, body style).

CompanyDim – Manufacturer and brand information.

DateDim – Calendar hierarchy for YTD/MTD analysis.

Data was cleaned and aggregated in SQL using joins and CTEs before loading into Power BI via DirectQuery.

5. Features / Highlights
• Business Problem

Dealerships lacked a unified system to monitor regional sales, model performance, and growth trends. Manual reports made it hard to identify underperforming areas or forecast demand accurately.

• Goal of the Dashboard

To develop a data pipeline and analytics layer that:

Extracts and aggregates sales data using SQL queries.

Visualizes key KPIs (YTD/MTD Sales, Growth %, Avg. Price, Cars Sold).

Provides regional, model, and dealer-level insights.

Supports business planning and inventory management.

• Walkthrough of Key Visuals
Overview Page

Top KPIs:

YTD Total Sales – $371M

YTD Avg Price – $28K

YTD Cars Sold – 13.3K

Growth – +19.73%

Weekly Sales Trend (Line Chart): Displays weekly fluctuations for performance tracking.

Sales by Body Style & Color (Donut Charts): Highlights preferences (SUV, Sedan, Hatchback; White & Black).

Dealer Region Map: Plots regional performance across Austin, Scottsdale, and Pasco.

Company Sales Trend (Bar Chart): Compares manufacturers (Ford, Chevrolet, Dodge, Mitsubishi, etc.) by YTD sales.

Details Page

Interactive Table: Displays transactional records (Car ID, Date, Dealer, Model, Color, Total Sales).

Dynamic Filters: Body Style, Dealer Region, Engine, and Transmission.

Consistent Header KPIs: Mirror top metrics for contextual awareness.

• SQL Tasks Involved

Created views and stored procedures to aggregate daily, monthly, and YTD sales.

Used joins and window functions to calculate rank, growth %, and averages.

Applied CTEs and CASE statements for data grouping and classification.

Optimized queries for faster Power BI DirectQuery performance.

• Business Impact & Insights

Enhanced visibility into top-performing regions, dealers, and car models.

Improved sales planning with accurate YTD vs MTD growth analysis.

Automated reporting process, reducing manual work by 40%.

Enabled data-backed pricing and inventory strategies for dealerships.

6. Screenshots / Demos
https://github.com/Mayuri-ai/Car-Sales-Analysis/blob/main/Car%20SalesDashboad_DetailsScreenshot.png
https://github.com/Mayuri-ai/Car-Sales-Analysis/blob/main/Car%20Sales%20Dashboard_OverviewScreenshot.png
