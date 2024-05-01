# Zomato-Dashboard

Methodology

The analysis of the Zomato restaurant dataset involved comprehensive data preparation, modeling, and visualization techniques using Power BI:

Data Preparation:
Utilized Power Query Editor for initial data cleansing and structuring.
Merged the users and restaurant tables to link related data.
Aligned data types across all columns to ensure consistency.
Unpivoted the sales_Quantity and sales_amount columns in the users table to enhance slicing capabilities.
Replaced null values in the city column with 'Others' for consistent data handling.

Data Modeling:
Established relationships between tables using primary and foreign keys.
Organized the data into a star schema with the orders table as the central fact table.

DAX Functions:
Created calculated columns and measures to enrich data analysis.
Implemented a dynamic ranking system for sales using a custom DAX function.
Developed measures to compute total sales values and perform dynamic sales ranking based on city and other criteria.

The Insights

The dashboard provided a detailed and multifaceted analysis of Zomato's operational metrics, encapsulating several key findings:

Yearly Sales Trends: A line graph vividly illustrated the yearly sales trends, showing significant fluctuations over the observed period (2017-2019). It highlighted a peak in sales during 2018, followed by a notable decline in subsequent years, capturing the volatility in market dynamics.
Metrics Cards Overview: The dashboard featured seven key metrics cards that displayed crucial data points:
Total Amounts and Quantities: Showcasing overall sales volume and the number of transactions.
Ratings: Providing insights into customer satisfaction and service quality.
Orders: Total number of orders processed.
Food Type Breakdown: Distribution between Veg, Non-Veg, and Others, indicating consumer preferences.
Sales Per City Analysis: A bar graph showed sales per city, enhanced by slicers allowing users to view sales rankings across different thresholds (All Sales, Top 10, Top 5). This revealed that Tirupati generated the highest sales, with significant contributions from cities like Electronic City and Pune.
Dynamic Sales Ranking: Utilizing the TopN_Sale measure, the dashboard dynamically adjusted the displayed data based on selected sales ranks. This feature effectively highlighted market trends and performance across different regions and periods, providing stakeholders with clear, actionable insights tailored to specific interests or concerns.
