# Global-Sales-Dashboard-


## Overview

This project focuses on comprehensive sales data analysis using Power BI. The analysis includes various dimensions such as region, sub-category, ship mode, category, market, segment, and profit trends year over year. The data has been processed using Power Query Editor and DAX queries to derive meaningful insights and visualizations.

## Analysis

Sales by Region: Evaluation of sales performance across different regions, identifying high-performing and underperforming areas.

Sales by Sub-Category: Detailed breakdown of sales within sub-categories to uncover trends and product performance.

Sales by Ship Mode: Analysis of how different shipping modes impact sales and delivery efficiency.

Sales by Category and Market: Insights into category-wise and market-wise sales distribution.

Sales by Segment and Profit Year Over Year: Understanding how different customer segments contribute to overall profit and sales growth.

KPI Cards by Country: Key Performance Indicators (KPIs) highlighting crucial metrics like total sales, profit, and growth rate per country.

Sales Forecasting: Predictive analysis based on the last two years' sales data, using decomposition to analyze trends by country, city, category, and sub-category.

Comparison Metrics: Year-over-year comparisons of sales and profit by country and market.

This integration of sales forecasting into our analysis provides a forward-looking perspective, allowing stakeholders to anticipate market demands and strategize accordingly.

The combination of historical analysis and predictive modeling offers a comprehensive view of sales dynamics, supporting effective planning and resource allocation.

## To make this fully functional, you would need to:

1. Add real data for the charts
2. Implement the map functionality
3. Connect the filters to update the visualizations
4. Add interactivity to the quarter selection buttons

## Data Processing

Power Query Editor:

Extracted year from the order date.

Cleaned data by replacing null values with 0.

Utilized postal codes for geographical segmentation.

## DAX Queries:

Calculated average delivery days using the DATEDIFF formula based on order and ship dates.

Problems Identified

Variability in sales performance across regions and segments.

Inconsistent profit margins in certain markets.

Delivery delays affecting customer satisfaction in specific shipping modes.

## Conclusion

This analysis provides actionable insights into sales trends, operational efficiencies, and growth opportunities. By leveraging Power BI's data visualization capabilities and DAX for advanced calculations, the project highlights key business areas for strategic improvements.


