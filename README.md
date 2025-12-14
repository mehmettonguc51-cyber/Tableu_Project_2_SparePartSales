# Global Sales Analysis Dashboard

## Project Overview
This project is a **Tableau-based Sales Analysis Dashboard** designed to provide a high-level overview of global sales performance. The dashboard enables stakeholders to track key metrics such as total revenue, sales trends over time, product performance, and geographic distribution of sales.

By visualizing transaction data, this project aims to answer critical business questions:
* *Which countries are generating the most revenue?*
* *How are sales trending across different years and months?*
* *Which product lines are the top performers?*
* *What is the distribution of deal sizes (Small, Medium, Large)?*

## Dataset Description
The analysis is based on the **Sales Sample Data** (`Sales Sample Data.csv`), which contains historical sales transaction records.

* **Data Source:** Sample sales transaction dataset.
* **Key Columns:**
    * `ORDERDATE`, `YEAR_ID`, `MONTH_ID`: Temporal data for trend analysis.
    * `SALES`, `QUANTITYORDERED`: Quantitative metrics for revenue and volume.
    * `PRODUCTLINE`: Categorical data for product segmentation (e.g., Classic Cars, Motorcycles).
    * `COUNTRY`, `CITY`, `TERRITORY`: Geographic data for regional analysis.
    * `DEALSIZE`: Categorical data indicating the size of the transaction.
    * `STATUS`: The current status of the order (e.g., Shipped, Resolved, On Hold).

## Dashboard Features & Insights
The Tableau dashboard visualizes the data through the following key components:

1.  **Sales by Product Line:** A breakdown of revenue across different product categories, highlighting which lines (e.g., Classic Cars) drive the most value.
2.  **Geographic Sales Distribution:** A map or regional chart showing sales concentration by country, identifying key markets like the USA and EMEA regions.
3.  **Sales Trend Analysis:** Time-series visualizations displaying sales performance over years and months to identify seasonal patterns and growth trends.
4.  **Deal Size Analysis:** A segmentation of orders by deal size (Small, Medium, Large) to understand the composition of revenue sources.

## Tools & Technologies
* **Tableau Public / Desktop:** Used for data visualization and dashboard creation.
* **Microsoft Excel / CSV:** Used for initial data inspection and storage.

