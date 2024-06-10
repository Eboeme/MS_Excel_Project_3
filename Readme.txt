Europe Sales Performance Dashboard

About
The dataset comprises European sales records, including details about countries, item types, sales channels, order information, shipping details, and financial metrics. It provides insights into customer behavior, product performance, regional trends, and potential areas for optimization to enhance sales and profitability.

Purpose of the Project
This project aimed to gain insights into the dataset and create a dashboard in Excel based on the following categories.

About Data
Column	Description
Country	The country where the sales occurred
Item Type	The type of item sold
Sales Channel	The sales channel through which the item was sold (Online/Offline)
Order ID	The order identity number
Order Priority	The priority level of the order
Order Date	The date on which the order was placed
Ship Date	The date on which the order was shipped
Days to Ship	The number of days taken to ship the order
Units Sold	The number of units sold
Cost Price	The cost price per unit of the item
Total Cost	The total cost of the order (Units Sold * Cost Price)
Selling Price	The selling price per unit of the item
Total Revenue	The total revenue from the order (Units Sold * Selling Price)
Total Profit	The total profit from the order (Total Revenue - Total Cost)

Approach Used
Data Wrangling: This is the first step where inspection of data is done to ensure NULL values and missing values are detected and data replacement methods are used to replace missing or NULL values.

No null values were found in the dataset.

Feature Engineering: This step helps create pivot charts based on the dataset.

Dashboard and Pivot Tables
The dashboard created in Excel consists of five pivot tables and corresponding charts to provide a comprehensive view of sales performance across different dimensions.

Sales Over Time:

Pivot Table: Uses Order Date (year) and Order Date (month) as rows, and Total Revenue as values.
Chart: A pivot line chart with markers, illustrating trends in sales revenue over time.

Sales by Country:

Pivot Table: Uses Country as rows and Total Revenue as values.
Chart: A pivot pie chart in the shape of a doughnut, representing the distribution of sales revenue across different countries.

Item Performance by Sales Channel:

Pivot Table: Uses Item Type and Sales Channel as rows, and Total Revenue as values.
Chart: A pivot clustered column chart, analyzing the performance of different item types across sales channels (Online/Offline).

Sales by Order Priority:

Pivot Table: Uses Order Priority as rows and Total Revenue as values.
Chart: A pivot pie chart, depicting the revenue contribution of orders based on their priority levels.

Shipping Performance:

Pivot Table: Uses Days to Ship as rows and Total Revenue as values.
Chart: A clustered bar chart, showing the impact of shipping times on sales revenue.

Slicers and Interactivity
The dashboard incorporates five slicers to allow for interactive filtering and deeper analysis:

Country: Filter the data to focus on specific countries.
Item Type: Analyze sales performance for specific types of items.
Sales Channel: Distinguish between online and offline sales channels.
Order Date (year): Narrow down the analysis to specific years.
Order Priority: Focus on orders based on their priority levels.
These slicers are connected to all pivot tables and charts, enabling users to dynamically explore the data and uncover actionable insights.

