# Global Superstore Analysis

### Objective
To create an interactive Power BI dashboard that explores the performance of **Global Superstores** focusing on KPIs and trends in sales.

**Tools Used:** Power BI

### Skills Demonstrated
- Analyzed 25k+ records and created a dashboard in Power BI
- Using Power Query Editor,
    - Removed irrelevant columns
    - Created calculated columns using DAX
    - Cleaned the dataset.
- Focused on minimal colours, drill downs and interactive storytelling.
- Used conditional formatting where needed.

### Dashboard Structure
**Page 1: Overview**
- *KPI Cards:* Total Sales, Total Profit, Profit Margin, No. of Orders
- *Bar Chart:* Sales by Category (drill-down to Sub-Category)
- *Map:* Sales by Country
- *Line Chart:* Profit Trend Over Time
- *Donut Chart:* Sales by Segment

<img width="945" height="541" alt="Screenshot 2025-10-22 182546" src="https://github.com/user-attachments/assets/78d4918f-f594-4b9f-8411-d17149ec373a" />

**Page 2: Sales Analysis**
- *Bar Chart:* Profit by Sub-category
- *Matrix:* Market vs Category Comparison (drill-down to Sub-Category)
- *Gauge Chart:* Profit Margin with its Target
- *Scatter Plot:* Profit Margin vs Sales (Profit as bubble)
- *Line Chart:* Monthly Sales Trend

<img width="1377" height="793" alt="Screenshot 2025-10-22 182655" src="https://github.com/user-attachments/assets/b16b089c-5c67-4e68-8289-c02470e1b945" />

**Page 3: Customer Analysis**
- *Bar Chart:* Orders by Market
- *Line Chart:* Profit by Segment Over Time
- *Tree Map:* Sales by Customer (Top 15)
- *Pie Chart:* Sales by Market

<img width="1377" height="797" alt="Screenshot 2025-10-22 182712" src="https://github.com/user-attachments/assets/776d5f5d-ab72-426f-bb45-eb161b2e6171" />


### 📊 Dataset Overview

| Column | Description |
|---------|--------------|
| category | The category of products sold in the superstore |
| city | The city where the order was placed |
| country | The country in which the superstore is located |
| customer_id | A unique identifier for each customer |
| customer_name | The name of the customer who placed the order |
| discount | The discount applied to the order |
| market | The market or region where the superstore operates |
| ji_lu_shu | An unknown or unspecified column |
| order_date | The date when the order was placed |
| order_id | A unique identifier for each order |
| order_priority | The priority level of the order |
| product_id | A unique identifier for each product |
| product_name | The name of the product |
| profit | The profit generated from the order |
| quantity | The quantity of products ordered |
| region | The region where the order was placed |
| row_id | A unique identifier for each row in the dataset |
| sales | The total sales amount for the order |
| segment | The customer segment (e.g., consumer, corporate, or home office) |
| ship_date | The date when the order was shipped |
| ship_mode | The shipping mode used for the order |
| shipping_cost | The cost of shipping for the order |
| state | The state or region within the country |
| sub_category | The sub-category of products within the main category |
| year | The year in which the order was placed |
| market2 | Another column related to market information |
| weeknum | The week number when the order was placed |
