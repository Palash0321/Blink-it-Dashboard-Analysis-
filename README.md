# Blink-it Dashboard Analysis
The Blinkit Dynamic Data Dashboard is a comprehensive and interactive Power BI solution designed to provide real-time, actionable insights into Blinkit's sales, customer behavior, and inventory performance from 2023-2025. It serves as a vital tool for stakeholders to monitor key business metrics, understand trends, and make data-driven decisions to optimize operations. The dashboard features a sleek, custom background designed using Figma, enhancing user experience.

# Project Overview
This project involved the end-to-end development of a sophisticated data dashboard for Blinkit. The primary goal was to transform raw sales, customer, and inventory data into meaningful visualizations and interactive reports. The process encompassed:

**Data Collection:** Gathering relevant data points for e-commerce operations.

**Data Cleaning & Wrangling:** Processing and refining raw data to ensure accuracy and consistency.

**Data Modeling:** Structuring data for efficient analysis and visualization.

**Data Visualization:** Creating intuitive charts and graphs to represent complex data.

**Dashboard Design:** Developing an aesthetically pleasing and user-friendly interface for easy navigation and insight discovery.

**Sharing Insights:** Presenting key performance indicators (KPIs) and trends to inform strategic decision-making.

The dashboard aims to enable corporate stakeholders to make informed decisions regarding sales forecasts, customer behavior, and product performance, ultimately contributing to increased sales and profitability

# Key Features
The Blinkit Dynamic Data Dashboard offers a range of interactive features designed for comprehensive analysis:

**Multi-Tab Navigation:** Organized into distinct sections (Home, Sales Overview, Customer, Feedbacks, Inventory, Marketing) for focused analysis.

**Dynamic KPIs:** Displays essential metrics with growth percentages, providing immediate performance snapshots.

**Interactive Visualizations:** Includes various charts like bar charts, line graphs, and donut charts, allowing users to interact with and explore data.

**Granular Filters:** Comprehensive filter panel for slicing data by date range (Last 2/3/6/9 Months, Last Month, Last 6 Months, YTD, TTD), Year (2023, 2024, 2025), Customer Name, Customer Segment, Area, and Product Name.

**Customizable Views:** Users can switch between Quantity and Value views for certain metrics to suit their analytical needs.

**Detailed Breakdowns:** Provides breakdowns of sales by top products/areas, quantities by payment methods, customer counts, and stock information.

**Customer Feedback Analysis:** Dedicated section to analyze customer ratings and feedback sentiment.

**Marketing Performance Tracking:** Visualizes marketing KPIs such as Clicks, Conversions, Impressions, Revenue, ROAS, and Spend over time.

# Technologies Used
The Blinkit Dynamic Data Dashboard was developed using a robust stack of tools:

**Python:** Utilized for data preparation and handling large datasets, including data cleaning and transformation.

**MySQL:** Employed for robust data storage, serving as the backend database.

**MySQL Workbench:** Used for database management, querying, and potentially for data manipulation within MySQL.

**Power BI:** The primary tool for dashboard creation, data modeling, and interactive visualization.

**Figma:** Used for designing the custom, sleek background and overall professional aesthetic of the dashboard.

# Dataset Used
The dataset powering this dashboard was self-created with the assistance of Python and ChatGPT. It consists of approximately 50,000 rows per table, encompassing data related to Blinkit's orders, customer feedback, sales, and inventory for the years 2023, 2024, and 2025.

<a href = "https://github.com/Palash0321/Blink-it-Dashboard-Analysis-/blob/main/createddata.py">Dataset</a>

# Overall KPIs
The dashboard highlights several crucial Key Performance Indicators (KPIs) across different sections:

**Total Quantity:** Overall quantity of goods sold.

**Total Value/Amount:** Total revenue generated from sales.

**Total Profit:** Overall profit earned.

**Customer Average Order Value (CAOV):** The mean value of orders placed by customers

**Growth Percentage:** Month-over-month or period-over-period growth for various metrics.

**Marketing Metrics:** Clicks, Conversions, Impressions, Revenue, Return on Ad Spend (ROAS), and Marketing Spend.

**Stock Metrics:** Total Received Stock, Available Stock (value and percentage), and Damaged Stock (value and percentage).

**Customer Feedback Metrics:** Count of feedbacks by rating (1-5), and overall positive/negative/neutral feedback percentages.

# Queries
The Blinkit Dynamic Data Dashboard answers a variety of critical business questions, enabling stakeholders to gain deep insights into operations:

**General/Overall Sales Queries:**

What is the total quantity of goods sold for the current period (e.g., Last 6/9 Months, 2024)?

What is the total sales value (revenue) for the current period?

What is the growth percentage for quantity and value compared to the previous period?

**Sales Overview Specific Queries:**

How much total sale is being made in each state? 

What is the total quantity sold for each of the product categories (e.g., top 50 products quantity)? 

What is the monthly profit trend? 

What is the total sales amount by customer? 

What is the total quantity sold for each payment mode? 

What is the total profit for each of the sub-categories of products? 

What is the sales overview and growth by month for 2023 and 2024?

**Customer Specific Queries:**

What is the top customer quantity?

What is the customer count by month?

What are the sales figures for customers who have ordered more than a certain number of times?

What are the details of customer orders, categories, segments, and feedback types?

**Feedback Specific Queries:**

What is the distribution of customer feedback ratings (1-5)?

What percentage of feedback is positive, negative, or neutral?

What are the details of individual customer feedback?

**Inventory Specific Queries:**

What is the total received stock?

What is the current available stock and its percentage?

What is the current damaged stock and its percentage?

What are the stock trends over time (stock received, period value, damaged value, available stock)?

**Marketing Specific Queries:**

What are the key marketing metrics (Clicks, Conversions, Impressions, Revenue, ROAS, Spend) for a given period?

How have marketing values (e.g., impressions, revenue generated) trended by month over time?

# Dashboard Controls and Filters
The dashboard provides extensive interactive controls for dynamic data exploration:

**Date Axis Filters:** Users can filter data by specific timeframes:
Last 2 Months

Last 3 Months

Last 6 Months

Last 9 Months

Last Month

Last 6 Months

Year To Date (YTD)

Total To Date (TTD)

**Year Selector:** Allows selection of data for specific years (2023, 2024, 2025).

**Customer Name Filter:** Enables filtering by individual customer names.

**Customer Segment Filter:** Allows selection based on customer segments (e.g., Inactive, New, Premium, Regular).

**Area Filter:** Filters data by geographical area.

**Product Name Filter:** Filters data by specific product names.

**Quantity/Value Toggle:** A button to switch between displaying metrics in terms of "Quantity" or "Value."

**Feedback Rating Selectors:** Allows selection/deselection of specific feedback ratings (1-5).

**Customer Order Count Filter:** A numeric input to filter customers who have ordered more than a specified number of times.

**Dashboard Interaction:** <a href ="https://github.com/Palash0321/Blink-it-Dashboard-Analysis-/blob/main/Home%20Page.png">Page1</a>


