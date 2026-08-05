Global Sales & Profit Performance Dashboard
 Project Overview

The Global Sales & Profit Performance Dashboard is an interactive Business Intelligence solution developed in Power BI to analyze global sales performance, profitability, and operational efficiency using a dataset containing 100,000 sales records. The dashboard transforms large volumes of transactional sales data into meaningful business insights through interactive visualizations, dynamic KPIs, and time-based analysis.

Designed with executives and business stakeholders in mind, the report provides a centralized view of financial and operational performance, enabling users to monitor business health, evaluate trends, identify growth opportunities, and make data-driven decisions with confidence.

The dashboard consists of two interactive report pages:

Executive Overview – Provides a high-level summary of sales performance, revenue trends, and market distribution.
Profit & Operations – Focuses on profitability, operational efficiency, cost analysis, and shipping performance.
 Problem Statement

Organizations generate thousands of sales transactions across different countries, regions, products, and sales channels every day. While this data contains valuable business information, it often exists in raw spreadsheets or databases that make analysis time-consuming and difficult.

Business leaders frequently need answers to questions such as:

How much revenue and profit is the business generating?
Is performance improving compared to the previous year?
Which regions and countries contribute the most revenue?
Which product categories are driving profitability?
Which sales channel performs better?
How efficient are operational processes such as shipping?
Where should future investments be focused?

Without an interactive reporting solution, these questions require extensive manual analysis, delaying decision-making and increasing the risk of overlooking important business trends.

This project addresses these challenges by transforming raw sales data into an executive-level dashboard that provides real-time insights into financial performance, operational efficiency, and overall business growth.

 Business Objectives

The primary objective of this project is to develop a centralized Business Intelligence dashboard that enables stakeholders to:

Monitor company-wide sales and profitability.
Compare current performance against the previous year.
Track Year-over-Year (YoY) business growth.
Analyze revenue across regions, countries, and product categories.
Evaluate operational efficiency using shipping performance metrics.
Compare Online and Offline sales performance.
Identify opportunities to improve profitability and operational processes.
Support strategic business planning through data-driven insights. Dataset Information
Attribute	Details
Dataset	Global Sales Dataset
Dataset Size	100,000 Sales Records
Time Period	2010 – 2017
Sales Channels	Online & Offline
Coverage	Multiple Countries & Global Regions
Product Categories	Multiple Item Types
Metrics	Revenue, Profit, Cost, Orders, Units Sold, Shipping Days
Dashboard Structure
Page 1 – Executive Overview

The Executive Overview page provides a comprehensive snapshot of the company's overall sales performance, allowing executives to monitor key business metrics at a glance.

Executive KPIs
KPI	Current Value	YoY Performance
Total Revenue	133.61 Billion	▲ 14.9% vs Previous Year
Total Orders	100K	▲ 15.0% vs Previous Year
Total Profit	39.41 Billion	▲ 15.0% vs Previous Year
Units Sold	500 Million	▲ 14.9% vs Previous Year
Visualizations
Revenue Trend by Month
Revenue by Region
Revenue by Country
Revenue by Item Type
Online vs. Offline Revenue Distribution
Interactive Filters (Region and Year)
Page 2 – Profit & Operations

The Profit & Operations page focuses on operational efficiency, profitability, and business performance drivers.

Operational KPIs
KPI	Current Value	YoY Performance
Total Cost	94.20 Billion	▲ 14.9% vs Previous Year
Average Profit per Order	394.09K	▼ 0.0% vs Previous Year
Average Revenue per Order	1.34 Million	▼ 0.1% vs Previous Year
Average Shipping Days	25.04 Days	▼ 0.1% vs Previous Year
Visualizations
Profit Trend by Month
Profit by Region
Profit by Item Type
Units Sold by Month
Online vs. Offline Profit Distribution
Interactive Filters (Region and Year)
Technical Approach

The dashboard was developed following a structured Business Intelligence workflow to ensure data accuracy, report performance, scalability, and user experience.

1. Data Preparation

The raw sales dataset was imported into Power BI and transformed using Power Query.

Key preparation tasks included:

Reviewing missing values
Standardizing data types
Removing unnecessary columns
Validating date fields
Ensuring data consistency
Preparing the dataset for efficient analysis
2. Data Modeling

A scalable data model was designed to improve report performance and support advanced calculations.

The modeling process included:

Creating relationships between tables
Implementing a Star Schema model
Building a dedicated Calendar table
Marking the Calendar table as the official Date Table
Optimizing relationships for Time Intelligence calculations
3. DAX Development

Custom DAX measures were developed to calculate key business metrics and performance indicators.

Measures created include:

Total Revenue
Total Profit
Total Cost
Total Orders
Units Sold
Average Revenue per Order
Average Profit per Order
Average Shipping Days
Previous Year (PY) Measures
Year-over-Year (YoY) Growth
Dynamic KPI Indicators
Conditional Color Formatting

Time Intelligence functions were implemented to enable dynamic comparisons between current and previous-year performance.

4. Dashboard Design

The report was designed using modern Business Intelligence best practices with a focus on usability and executive reporting.

Design features include:

Executive-friendly dashboard layout
Dark-themed interface for improved readability
Interactive slicers for dynamic filtering
KPI cards with sparklines
Consistent color palette
Responsive visual arrangement
Minimal visual clutter
Cross-filtering between visuals

The result is an intuitive dashboard that allows users to explore business performance quickly and efficiently.

 Tools & Technologies Used
Tool / Technology	Purpose
Power BI Desktop	Dashboard development and interactive reporting
Power Query	Data extraction, cleaning, and transformation
DAX (Data Analysis Expressions)	KPI calculations, measures, and Time Intelligence
Data Modeling	Relationship management and Star Schema implementation
Calendar Table	Date Intelligence and Year-over-Year analysis
Power BI Maps	Country-level geographical analysis
Interactive Slicers	Dynamic report filtering
Conditional Formatting	KPI performance indicators and visual highlighting
 Key Insights
The business generated 133.61 Billion in total revenue, representing a 14.9% Year-over-Year increase, indicating sustained business growth.
Total profit reached 39.41 Billion, reflecting a 15.0% increase compared to the previous year, demonstrating healthy profitability.
The company processed 100,000 orders and sold over 500 Million units, highlighting strong operational capacity and customer demand.
Total operational cost amounted to 94.20 Billion, increasing by 14.9%, closely aligned with overall revenue growth.
Europe and Sub-Saharan Africa emerged as the strongest-performing regions, while North America generated comparatively lower revenue, presenting opportunities for expansion.
Revenue distribution across countries reveals key markets driving sales while identifying countries with growth potential.
Household and Office Supplies generated the highest revenue, making them the company's strongest-performing product categories.
Fruits and Beverages contributed the least revenue, suggesting opportunities for product optimization or targeted marketing initiatives.
Online and Offline channels contribute almost equally to overall revenue and profit, indicating a balanced multi-channel sales strategy.
The average shipping time of 25.04 days suggests room for improving logistics efficiency and customer satisfaction.
While total revenue and profit increased significantly, the Average Revenue per Order and Average Profit per Order remained relatively unchanged year-over-year, indicating that business growth was driven primarily by increased sales volume rather than higher-value transactions.
 Business Recommendations

Based on the insights generated from the dashboard, the following recommendations are proposed:

Expand High-Performing Markets

Increase investment in high-performing regions and countries by strengthening distribution channels, expanding product availability, and implementing customer retention strategies.

Improve Performance in Low-Revenue Markets

Conduct market research to identify barriers affecting lower-performing countries and implement localized pricing strategies, promotional campaigns, and targeted marketing initiatives.

Focus on High-Performing Product Categories

Allocate additional inventory, marketing resources, and promotional efforts toward high-performing categories such as Household and Office Supplies to maximize revenue growth.

Reassess Low-Performing Products

Evaluate the pricing, demand, and profitability of lower-performing product categories such as Fruits and Beverages. Consider product repositioning, promotional offers, or inventory optimization to improve overall performance.

Optimize Logistics Operations

Reduce average shipping time by improving warehouse operations, strengthening supplier coordination, and partnering with more efficient logistics providers.

Maintain a Balanced Sales Strategy

Continue investing in both Online and Offline sales channels while identifying opportunities to enhance customer experience and increase digital engagement.

Monitor Business Performance Continuously

Regularly monitor Year-over-Year KPIs and operational metrics to identify emerging trends, measure business performance, and support proactive decision-making.

 Skills Demonstrated

This project showcases practical experience in:

Business Intelligence
Data Visualization
Dashboard Design
Data Cleaning
Data Transformation
Power Query
Data Modeling
Star Schema Design
DAX Development
Time Intelligence
KPI Development
Executive Reporting
Business Analytics
Data Storytelling
Performance Analysis
 Dashboard Preview
Executive Overview

Provides executives with a high-level view of business performance, including revenue, profit, order volume, regional analysis, country performance, product contribution, and sales channel distribution.

Profit & Operations

Delivers operational insights through cost analysis, profitability metrics, shipping performance, monthly profit trends, units sold, and product-level profitability to support strategic operational improvements.

Add your dashboard screenshots here

Executive Overview

Profit & Operations

 Conclusion

The Global Sales & Profit Performance Dashboard demonstrates how Business Intelligence can transform a 100,000-row global sales dataset into a comprehensive decision-support solution. Through effective data preparation, robust data modeling, advanced DAX calculations, and intuitive visualizations, the dashboard provides stakeholders with clear visibility into sales performance, profitability, and operational efficiency.

By combining financial KPIs, Year-over-Year analysis, geographic insights, and operational metrics within an interactive reporting environment, the solution empowers decision-makers to identify growth opportunities, optimize business performance, and make informed strategic decisions with confidence.

This project highlights not only technical proficiency in Power BI, Power Query, DAX, and data modeling, but also the ability to translate complex business data into actionable insights through effective storytelling and executive-focused dashboard design.
