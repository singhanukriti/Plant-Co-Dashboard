# Plant-Co-Dashboard
Interactive Sales Performance Dashboard – Power BI Portfolio Project
Developed a dynamic Power BI dashboard for analyzing sales, profitability, and product performance. It covers the complete workflow from data preparation (Power Query) to advanced DAX, dynamic KPIs, and interactive data visualizations. 

This repository features an end-to-end sales analytics dashboard built in Power BI, showcasing best-practice data modeling, transformation, and visualization. The project demonstrates the process of cleaning and shaping raw sales, accounts, and product hierarchy data, developing key business DAX measures (including dynamic switch metrics and date intelligence), and designing interactive report visuals. The dashboard provides actionable insights into sales trends, product performance, and profitability with professional layout and slicers for dynamic user exploration.

The dashboard was built using following tools and technologies:
- Power BI Desktop: The central tool for data modeling, report building, and visualization creation.
- Power Query: Used for importing, cleaning, and transforming raw data (such as sales, accounts, and product details) into analysis-ready formats.
- DAX (Data Analysis Expressions): Core for building calculated columns, measures, and custom KPIs (like dynamic sales, cost, gross profit, and time-intelligence metrics such as year-to-date and prior year calculations).
- Custom Date Table: Built in Power BI using DAX for accurate date-based computations and time intelligence.
- Relationship Modeling: Designing and managing relationships between fact and dimension tables to enable accurate cross-filtering and aggregations.
- Interactive Visualizations: Utilizing charts, cards, treemaps, waterfall graphs, and slicers for dynamic analysis and user-driven insights.
- Conditional Formatting and Dynamic Titles: Enhancements for better storytelling and user experience in reports.
- Automated Data Refresh: Power BI provides scheduled data refreshes to keep your dashboard up-to-date, especially when publishing to the Power BI Service.
- Professional Layouts: Use of backgrounds (such as those created in PowerPoint) for polished report aesthetics.

Source: kaggle.com
The raw data represents individual business transactions from a company's sales operations.
The raw data tracks all transactions at the lowest level—who bought what, when, at what price, and at what cost.
It captures the financial (revenue, cost), operational (quantities), and timing (date) details needed to answer any sales performance question.

Business Problem:
The business needed a clear, data-driven understanding of its sales operations: Which products, markets, or accounts drive the most revenue and profit? Where are margins high or low? Are there seasonal or yearly trends to address? Which products or customers may need more attention or strategic action?

Goal of the Dashboard:
- Transform granular sales data into actionable business insights.
- Empower decision-makers to quickly identify sales trends, best and worst performers, and profit drivers.
- Provide interactive exploration: break down performance by product, account, and time period.

Walkthrough of Key Visuals:
- KPI Cards: Big numbers for Total Sales, Quantity Sold, Gross Profit, and Profit Margin offer at-a-glance performance metrics.
- Switchable Visuals: Users can toggle charts to show Sales, Profit, or Quantity—quickly zeroing in on what matters for different reporting scenarios.
- Treemaps & Categories: Visual breakdowns of sales/profit by product hierarchy or customer/account segment reveal which categories or clients are driving results or lagging.
- Waterfall/Combo Charts: Track trends over time (monthly/quarterly/yearly), and pinpoint spikes or dips, helping to understand underlying business cycles or anomalies.
- Scatter Plots or Outlier Charts: Compare COGS, price, or gross margin by product/account—find outliers with high sales but low profit, or vice versa.
- Dynamic Titles & Conditional Formatting: Report page adjusts context based on user slicer/filters (such as “Top 5 Products by Profit in Q1 2023”), with red/yellow/green formatting highlighting areas of concern or opportunity.

Business Impact & Insights:
- Rapid Performance Assessment: Management sees instantly which products or customers contribute most to sales and profit.
- Opportunity Detection: Underperformers (products/accounts/regions/times with low sales or margins) can be quickly targeted for improvement.
- Margin Optimization: By exposing where COGS eats into profit, the dashboard helps identify cost-saving or price-optimization possibilities.
- Trend Analysis: Time-based visuals reveal seasonal effects, growth or decline, and inform future planning or budget forecasts.
- Interactivity: Filters allow users to drill into specific products, customers, or periods, supporting ad hoc analysis, routine reviews, or board reporting.

Dashboard Preview:
![Dashboard Preview](https://github.com/singhanukriti/Plant-Co-Dashboard/blob/main/Dashboard%20Preview.png)
