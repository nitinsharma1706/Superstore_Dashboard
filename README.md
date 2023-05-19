# Project Name: Superstore_Dashboard

## Introduction

The Sales Superstore Dashboard project aims to analyze and visualize the sales performance of a retail company using the Sales Superstore dataset. The dashboard provides actionable insights into sales trends, customer behavior, product performance, geographical analysis, order and shipping data, and profitability. By leveraging data visualization and analytics, the dashboard helps optimize sales, improve customer management, and drive business growth.

## Problems aimed to solve
- Sales Analysis
- Product Performance and Inventory Management
- Geographical Analysis and Market Insights
- Order and Shipping Analysis
- Profitability and Cost Analysis

## Data Description

- Table 1: Orders

Column Name     | Description
----------------|-------------------------------------
Order Date      | The date when the order was placed
Ship Date       | The date when the order was shipped
Ship Mode       | The mode of shipment for the order
Customer ID     | Unique identifier for each customer
Customer Name   | Name of the customer
Segment         | Market segment to which the customer belongs
Postal Code     | Postal code of the customer's location
City            | City where the customer is located
State           | State where the customer is located
Country         | Country where the customer is located
Region          | Region where the customer is located
Market          | Market segment to which the customer belongs
Product ID      | Unique identifier for each product
Category        | Category of the product
Sub-Category    | Sub-category of the product
Product Name    | Name of the product
Sales           | Total sales revenue for the order
Quantity        | Quantity of products ordered
Discount        | Discount applied to the order
Profit          | Profit earned from the order
Shipping Cost   | Cost of shipping the order
Order Priority  | Priority level of the order

- Table 2: Returns

Column Name | Description
------------|------------------------------------
Returned    | Indicates whether the order was returned or not
Order ID    | Unique identifier for each order
Region      | Region where the order was placed or returned

- Table 3: People

Column Name | Description
------------|------------------------------------
Person      | Name or identifier of a person
Region      | Region associated with the person

## Methodlogy

- **Dataset Preparation**: The Superstore sales data is obtained and imported into Power Query for data cleaning and transformation.

- **Data Cleaning and Transformation**: Using Power Query, the data is cleaned by removing irrelevant columns, filtering out unnecessary data, and handling missing values. Transformation steps are applied to ensure the data is in a suitable format for analysis.

- **Dashboard Design**: The cleaned dataset is connected to Power BI, where an interactive and visually appealing dashboard is designed. Various visualizations, such as charts, and graphs, are added to present key insights from the sales data.

- **Interactive Filters**: Filters are implemented in the dashboard to allow users to slice and dice the data based on different dimensions like region, Segment, and product. This enhances the exploratory capabilities of the dashboard.

- **Calculated Measures**: Using the DAX formula language, calculated measures are created to derive additional insights from the data. Examples of calculated measures include sales growth, and sum of sales.

<p align="left"> <img src="https://drive.google.com/uc?export=download&id=1WcqPiX9FT8v-0v0nL6rf9-0Tq5ziRJTx" alt="Dashboard" /> </p>

## Results

- Among all the regions, Asia Pacific exhibits the highest sales, while Africa has the lowest sales across the board.

- The year 2015 stands out with the highest sales compared to all the other years in the dataset.

- The consumer segment demonstrates the highest sales volume, followed by the corporate segment, and finally the home offices segment.

- The product with the maximum profit in the dataset is the Ebico Electric Binding Machine, indicating strong profitability. Conversely, the Hover Stove is identified as the product with the highest loss, reflecting a negative impact on overall profitability.


### Limitations and challenges.

- **Limited Interactivity:** Depending on the design and functionality of the dashboard, the level of interactivity and drill-down capabilities may be limited, restricting users' ability to explore data and gain deeper insights.

- **User Expertise:** The dashboard assumes that users have a basic understanding of data analysis and interpretation. Users with limited data literacy or domain knowledge may face challenges in effectively utilizing the dashboard.

- **Challenges:** Limited knowledge of DAX language requires learning it for the project, including understanding syntax, complex calculations, optimization and staying updated with DAX's evolving features.

