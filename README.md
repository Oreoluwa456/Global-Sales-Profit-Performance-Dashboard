
# Global Sales & Profit Performance Dashboard

## Project Overview

The **Global Sales & Profit Performance Dashboard** is an interactive Business Intelligence solution developed in **Power BI** to analyze global sales performance, profitability, and operational efficiency using a dataset containing **100,000 sales records**. The dashboard transforms large volumes of transactional sales data into meaningful business insights through interactive visualizations, dynamic KPIs, and time-based analysis.

Designed with executives and business stakeholders in mind, the report provides a centralized view of financial and operational performance, enabling users to monitor business health, evaluate trends, identify growth opportunities, and make informed decisions backed by data.

The dashboard consists of two interactive report pages:

- **Executive Overview** – Provides a high-level summary of sales performance, revenue trends, and market distribution.
- **Profit & Operations** – Focuses on profitability, operational efficiency, cost analysis, and shipping performance.

## Problem Statement

Organizations generate thousands of sales transactions across different countries, regions, products, and sales channels every day. Although this information contains valuable business insights, it often exists in raw spreadsheets or disconnected systems that make analysis slow and inefficient.

Business leaders need quick answers to questions such as:

- How much revenue and profit is the business generating?
- Is business performance improving compared to previous years?
- Which countries and regions contribute the most revenue?
- Which product categories generate the highest profit?
- How do Online and Offline sales channels compare?
- How efficient is the company's shipping process?
- Where should management focus future investments?

Without a centralized reporting solution, these questions require extensive manual analysis, delaying decision-making and increasing the likelihood of overlooking important trends.

This project addresses these challenges by transforming raw sales data into an interactive executive dashboard that delivers clear, actionable insights into financial performance, operational efficiency, and business growth.

## Business Objectives

The primary objective of this project is to develop a centralized Business Intelligence dashboard that enables stakeholders to:

- Monitor company-wide sales and profitability.
- Compare current performance against the previous year.
- Track Year-over-Year (YoY) business growth.
- Analyze revenue across regions, countries, and product categories.
- Evaluate operational efficiency using shipping performance metrics.
- Compare Online and Offline sales performance.
- Identify opportunities to improve profitability and operational processes.
- Support strategic business planning through data-driven insights.

## Dataset Information

**Dataset:** Global Sales Dataset

**Dataset Size:** 100,000 Sales Records

**Time Period:** 2010 – 2017

**Sales Channels:** Online & Offline

**Coverage:** Multiple Countries and Global Regions

**Product Categories:** Multiple Item Types

**Metrics Analyzed:** Revenue, Profit, Cost, Orders, Units Sold, Shipping Days

# Dashboard Structure

## Executive Overview

The **Executive Overview** page provides a comprehensive snapshot of the company's overall sales performance, allowing executives to monitor key business metrics at a glance.

### Executive KPIs

**Total Revenue:** **133.61 Billion** | **▲ 14.9% vs Previous Year**

**Total Orders:** **100K** | **▲ 15.0% vs Previous Year**

**Total Profit:** **39.41 Billion** | **▲ 15.0% vs Previous Year**

**Units Sold:** **500 Million** | **▲ 14.9% vs Previous Year**

### Dashboard Visuals
- Revenue Trend by Month
- Revenue by Region
- Revenue by Country
- Revenue by Item Type
- Online vs. Offline Revenue Distribution
- Interactive slicers Year and Order Priority

## Profit & Operations

The **Profit & Operations** page provides deeper insight into profitability, cost management, and operational performance, helping stakeholders evaluate how efficiently the business operates.

### Operational KPIs

**Total Cost:** **94.20 Billion** | **▲ 14.9% vs Previous Year**

**Average Profit per Order:** **394.09K** | **▼ 0.0% vs Previous Year**

**Average Revenue per Order:** **1.34 Million** | **▼ 0.1% vs Previous Year**

**Average Shipping Days:** **25.04 Days** | **▼ 0.1% vs Previous Year**

### Dashboard Visuals

- Profit Trend by Month
- Profit by Region
- Profit by Item Type
- Units Sold by Month
- Online vs. Offline Profit Distribution
- Interactive slicers for Region and Year

# Technical Approach

The dashboard was developed following a structured Business Intelligence workflow to ensure data accuracy, report performance, scalability, and an intuitive user experience.

## 1. Data Preparation

The raw sales dataset was imported into Power BI and transformed using **Power Query**.

The preparation process included:

- Reviewing missing values
- Standardizing data types
- Removing unnecessary columns
- Validating date fields
- Ensuring data consistency
- Preparing the dataset for efficient analysis

## 2. Data Modeling

A scalable data model was designed to improve report performance and support advanced analytical calculations.

The modeling process included:

- Creating relationships between tables
- Implementing a Star Schema model
- Building a dedicated Calendar table
- Marking the Calendar table as the official Date table
- Optimizing relationships for Time Intelligence calculation.

## 3. DAX Development

Custom DAX measures were developed to calculate business metrics and performance indicators.

Key measures include:

- Total Revenue
- Total Profit
- Total Cost
- Total Orders
- Units Sold
- Average Revenue per Order
- Average Profit per Order
- Average Shipping Days
- Previous Year (PY) Measures
- Year-over-Year (YoY) Growth
- Dynamic KPI Indicators
- Conditional Color Formatting

Time Intelligence functions were implemented to enable dynamic comparisons between current and previous-year performance.

## 4. Dashboard Design

The report was designed using modern Business Intelligence best practices with a strong focus on usability, readability, and executive reporting.

Key design considerations include:

- Executive-friendly dashboard layout
- Dark-themed interface for improved readability
- Interactive slicers for dynamic filtering
- KPI cards with sparklines
- Consistent color palette
- Responsive visual arrangement
- Minimal visual clutter
- Cross-filtering between visuals

# Tools & Technologies Used

- Power BI Desktop:** Dashboard development and interactive reporting
- Power Query:** Data extraction, cleaning, and transformation
- DAX (Data Analysis Expressions):** KPI calculations, custom measures, and Time Intelligence
- Data Modeling:** Relationship management and Star Schema implementation
- Calendar Table:** Date intelligence and Year-over-Year analysis
- Power BI Maps:** Country-level geographical analysis (Azure Map)
- Interactive Slicers:** Dynamic report filtering
- Conditional Formatting:** KPI indicators and performance highlighting

# Key Insights

The dashboard reveals several important business insights that can support strategic decision-making.

### Overall Business Performance

- The business generated **133.61 Billion** in total revenue, representing a **14.9% Year-over-Year increase**, demonstrating consistent business growth.
- Total profit reached **39.41 Billion**, reflecting a **15.0% increase** compared to the previous year, indicating strong profitability.
- The company processed approximately **100,000 orders** and sold over **500 Million units**, highlighting strong customer demand and operational capacity.
- Total operational cost amounted to **94.20 Billion**, increasing by **14.9%**, closely aligning with overall revenue growth.

### Regional Performance

- Europe and Sub-Saharan Africa emerged as the strongest-performing regions in terms of both revenue and profit.
- North America generated comparatively lower revenue, suggesting opportunities for market expansion and improved sales strategies.

### Country Performance

- Revenue distribution varies considerably across countries, highlighting key markets that drive overall business performance.
- Several countries consistently contribute a significant share of revenue, while others present opportunities for future growth through localized business strategies.

# Product Performance

- Household and Office Supplies generated the highest revenue, making them the company's strongest-performing product categories.
- Fruits and Beverages contributed the least revenue, indicating opportunities for pricing optimization, product repositioning, or targeted marketing campaigns.

# Sales Channel Performance

- Online and Offline sales channels contribute almost equally to total revenue and profit, demonstrating a well-balanced sales strategy across both channels.

# Operational Performance

- The average shipping time of **25.04 days** suggests room for improving logistics efficiency and enhancing customer satisfaction.
- Although overall revenue and profit increased significantly, **Average Revenue per Order** and **Average Profit per Order** remained relatively unchanged Year-over-Year, indicating that business growth was primarily driven by increased sales volume rather than higher-value transactions.

# Business Recommendations

Based on the insights generated from the dashboard, the following recommendations can help improve business performance and operational efficiency.

- Expand High-Performing Markets

Increase investment in high-performing regions and countries by strengthening distribution networks, expanding product availability, and implementing customer retention strategies to maximize long-term growth.

- Improve Performance in Low-Revenue Markets

Conduct market research to understand the factors limiting performance in lower-revenue countries. Introduce localized marketing campaigns, pricing strategies, and promotional activities to improve market penetration and customer acquisition.

- Focus on High-Performing Product Categories

Allocate additional inventory, marketing resources, and promotional efforts toward high-performing categories such as **Household** and **Office Supplies**, which consistently generate the highest revenue and profit.

- Reassess Low-Performing Products

Evaluate the pricing, demand, and profitability of lower-performing categories such as **Fruits** and **Beverages**. Consider repositioning these products, offering targeted promotions, or optimizing inventory levels to improve overall performance.

- Optimize Logistics Operations

Reduce average shipping time by improving warehouse operations, strengthening supplier coordination, and partnering with more efficient logistics providers. Faster deliveries can improve customer satisfaction and increase repeat business.

- Maintain a Balanced Sales Strategy

Continue investing in both Online and Offline sales channels while identifying new opportunities to improve customer engagement, digital marketing performance, and the overall buying experience.

- Monitor Performance Continuously

Regularly monitor Year-over-Year KPIs, profitability metrics, and operational indicators to identify emerging trends early, measure business performance accurately, and support proactive decision-making.

# Skills Demonstrated

This project demonstrates practical experience across multiple areas of Business Intelligence and Data Analytics, including:

- Business Intelligence Reporting
- Data Visualization
- Dashboard Design
- Data Cleaning and Transformation
- Power Query
- Data Modeling
- Star Schema Design
- DAX Development
- Time Intelligence
- KPI Development
- Executive Reporting
- Business Analytics
- Data Storytelling
- Performance Analysis
- Interactive Dashboard Development

# Dashboard Preview

## Executive Overview

The Executive Overview page provides decision-makers with a high-level summary of business performance through interactive KPIs, revenue trends, regional analysis, country-level performance, product contribution, and sales channel distribution.
# https://github.com/Oreoluwa456/Global-Sales-Profit-Performance-Dashboard/blob/main/Executive%20Overview.png


## Profit & Operations

The Profit & Operations page delivers deeper operational insights by analyzing profitability, costs, shipping performance, units sold, and product performance. It helps stakeholders understand operational efficiency and identify opportunities to improve business performance.
# https://github.com/Oreoluwa456/Global-Sales-Profit-Performance-Dashboard/blob/main/Profit%20And%20Operations.png

# Conclusion

The **Global Sales & Profit Performance Dashboard** demonstrates how Business Intelligence can transform a **100,000-row global sales dataset** into a comprehensive decision-support solution.

Using **Power BI**, **Power Query**, **DAX**, and a well-structured data model, the project converts complex transactional data into meaningful insights through interactive visualizations and executive-focused reporting.

The dashboard enables stakeholders to monitor key business metrics, evaluate financial performance, analyze regional and country-level sales, assess product profitability, compare sales channels, and measure operational efficiency using Year-over-Year analysis and dynamic KPIs.

Beyond presenting historical performance, the dashboard supports strategic decision-making by highlighting growth opportunities, identifying underperforming areas, and providing actionable recommendations based on data.

This project reflects not only technical proficiency in Business Intelligence tools but also the ability to understand business requirements, build scalable reporting solutions, and communicate insights through effective data storytelling.
# Author

## Ore Temitope Israel

Aspiring Data Analyst with a passion for transforming raw data into actionable business insights through Business Intelligence, data visualization, and analytical storytelling.

### Connect with me

- LinkedIn: *(Add your LinkedIn profile)*
- GitHub: *(Add your GitHub profile)*
- Email: *(oreisrael4@gmail.com)
