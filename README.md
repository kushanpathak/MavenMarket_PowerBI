Maven Market: Power BI Analysis


This project is an in-depth analysis of Maven Market, a fictional grocery store business dataset provided by Maven Analytics. Using Power BI, I explored sales transactions, returns, profits, and revenue trends across the United States, Mexico, and Canada to uncover key business insights and identify opportunities for improvement.

The analysis highlights performance gaps in Canada, steady growth in the United States and Mexico, and provides data-driven recommendations for business strategy.

Project Overview
Tool Used: Power BI

Dataset Source: Maven Analytics (CSV files – 8 tables)

Techniques Applied:

Data cleaning and transformation in Power Query

Data modeling with star and snowflake schemas

DAX measures for KPIs and aggregations

Dashboard creation with KPIs, matrix tables, maps, and time-series charts

Data Model
Fact tables: Transactions Data (1997–1998), Returns Data

Dimension tables: Products, Calendar, Regions, Stores, Customers

Schema: Combination of star schema (Regions & Stores) and snowflake schema (others)

Relationships: Many-to-one cardinality with single cross filter direction

Key DAX Measures
Total Transactions, Total Profit, Total Returns

Previous Month KPIs with CALCULATE() and DATEADD()

60-Day Rolling Revenue using DATESINPERIOD()

Total Cost using SUMX() with the RELATED() function

Return Rates using COUNTROWS() and DISTINCTCOUNT()

Dashboard Features
KPI Cards for Transactions, Profit, Returns, with prior month comparisons

Matrix Visual by Product Brand with conditional formatting

Map Visual for transactions by city, region, and country

Gauge Chart for current month revenue vs. target (+5% of prior month)

Weekly Revenue Trend using column chart

Insights
The United States and Mexico show healthy trends in transactions, profit, and low return rates.

Canada is underperforming with:

Lower transactions and profits

High volatility in revenue trends

Exceptionally high return rates (over 11%) across most brands

Strategic recommendation: close Canadian stores or consider revamping product assortment after detailed market research.

Potential Solutions
Conduct market research to adjust product offerings.

Improve quality control if return rates are linked to product defects.

Reallocate resources to the US and Mexican markets, which show steady growth.

Dashboard Preview

<img width="608" height="338" alt="image" src="https://github.com/user-attachments/assets/bfe04a20-0bab-4e76-8bec-f179532fab78" />



The Maven Market analysis demonstrates the power of data-driven decision making with Power BI. By exploring operations across three countries, I uncovered areas of strong performance, weaknesses in specific regions, and actionable strategies to optimize resources. This project enhanced my skills in data modeling, DAX, and storytelling through visuals.

About the Dataset
This project is based on Maven Analytics’ Maven Market dataset used in the Power BI Desktop for Business Intelligence course.
