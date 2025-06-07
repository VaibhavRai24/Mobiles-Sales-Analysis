
![image](https://github.com/user-attachments/assets/06c3e78c-799d-4b1e-b6c9-ca7e50c0d8aa)
📊 Samsung Mobile Sales Dashboard - Power BI
📌 Overview
This Power BI dashboard provides a comprehensive view of Samsung mobile sales performance across cities in India. It analyzes total sales, quantity sold, customer transactions, ratings, payment methods, and temporal trends. The dashboard is interactive and designed for both high-level summaries and granular insights.

📂 Dataset Summary
Rows: 3,800+

Fields Included:

Transaction ID

Brand

City

Mobile Model

Date, Day, Month

Quantity Sold

Price per Unit

Payment Method

Customer Rating

📌 Key KPIs (Top Cards)
Total Sales: ₹769M

Total Quantity Sold: 19K Units

Total Transactions: 4K

Average Sales per Transaction: ₹40K

🗺️ Visualizations Included
1. Total Sales by City (Map)
Geo-mapped bubble chart to visualize sales distribution by Indian cities.

2. Quantity Sold by Day (Line Chart)
Tracks daily quantity trends across January to identify peak days.

3. Total Sales by Mobile Model (Bar Chart)
Highlights best-selling Samsung and competitor models.

4. Transactions by Payment Method (Donut Chart)
Breaks down transactions by UPI, Cash, Debit, and Credit cards.

5. Customer Ratings (Bar + Line Charts)
Vertical bar chart shows count of 1–5 star ratings.

Line chart maps sales vs. customer satisfaction across weekdays.

6. Brand-wise Summary (Table)
Tabular data for major brands including:

Total Sales

Total Quantity

Count of Transactions

🧭 Interactivity Features
Month Filter (Slicer): Select any month (January–December) to filter all visuals.

Cross-highlighting: Interactive selection updates related charts dynamically.

🧮 Measures Used
Total_Sales = SUM('Mobiles_Sales'[Total Sales])

Total_Qty = SUM('Mobiles_Sales'[Total Quantity])

Total_Transactions = DISTINCTCOUNT('Mobiles_Sales'[Transaction ID])

Average = DIVIDE([Total_Sales], [Total_Transactions])

🎯 Purpose
This dashboard helps:

Analyze Samsung's market performance.

Identify top cities and models contributing to revenue.

Understand customer behavior and preferences.

Optimize marketing strategies by season, city, or payment method.

🔧 Tools Used
Microsoft Power BI Desktop

Excel (Data Source)

DAX Measures for calculated KPIs

Slicers & Filters for interactivity

