# data-analytics-task2
📊 Sales Performance Dashboard – Power BI

This project is created as part of Task 2 – Data Visualization & Storytelling for my Data Analyst Internship.

The objective of this task is to transform a raw sales dataset into an interactive and meaningful dashboard using Power BI, applying best practices in visualization and storytelling.

📝 Project Overview

The purpose of this dashboard is to analyze sales performance using KPIs and interactive charts.
It highlights customer behavior, product performance, regional trends, and overall business insights derived from the Superstore Sales dataset.

This visual report follows the internship requirements:

Choosing the right charts

Avoiding clutter

Highlighting key takeaways

Applying visual storytelling

Summarizing insights

📁 Dataset Used

Full_Superstore.csv
This dataset includes fields like:

Category, Sub-Category

Customer Name, Customer ID

Sales, Profit, Quantity

Region, State, City

Order Date, Ship Mode

🛠️ Tools Used

Power BI Desktop

📌 Steps Followed in This Project

1️⃣ Import Data

Open Power BI → Get Data → Text/CSV

Load Full_Superstore.csv

2️⃣ Data Cleaning & Preparation

Checked data types

Renamed fields where needed

Removed unnecessary columns

Created basic DAX measures:

Total Sales = SUM('Full_Superstore'[Sales])
Total Profit = SUM('Full_Superstore'[Profit])
Total Quantity = SUM('Full_Superstore'[Quantity])

3️⃣ Dashboard Layout Design

Created a clean and professional dashboard with a left-side navigation panel:

OVERVIEW

CUSTOMER PERFORMANCE

PRODUCT PERFORMANCE

SALES ANALYSIS

INSIGHTS & EXTRA NOTES

This improves readability and storytelling.

📊 Visuals Used in the Dashboard

Below are all charts created in this project.

📌 1. Sales by Category (Column Chart)

Fields:

X-axis → Category

Y-axis → Sales

Insight: Technology and Furniture contribute the most to sales.

📌 2. Profit by Sub-Category (TreeMap)

Fields:

Group → Sub-Category

Values → Profit

Insight: Phones and Chairs generate high profit; some categories show low profit margins.

📌 3. Sales by Region (Map)

Fields:

Location → State

Size/Values → Sales

Insight: Western region performs the best.

📌 4. Sales Trend by Order Date (Line Chart)

Fields:

X-axis → Order Date (Month hierarchy)

Y-axis → Sales

Insight: Sales show seasonal variation across months.

📌 5. Sales by Ship Mode (Donut/Pie Chart)

Fields:

Legend → Ship Mode

Values → Sales

Insight: Standard Class is the most preferred shipping method.

📌 6. Top 10 Customers by Sales (Bar Chart)

Fields:

Y-axis → Customer Name

X-axis → Sales

Filters: Top N → 10 → By Sales

Insight: Identifies the highest-value customers.

⭐ KPIs Displayed

Total Sales

Total Profit

Total Quantity Sold

Displayed at the top for quick decision-making.

🧠 Key Insights & Summary

Technology category drives maximum revenue.

Certain sub-categories underperform in profit.

West region leads in sales.

Seasonal trends impact order volume.

Top customers significantly influence total revenue.

Standard Class is the most used shipping method.

🚀 How to Use This Dashboard

Download the PBIX file

Open with Power BI Desktop

Interact with filters and visuals

Explore insights from KPIs and charts

📎 Repository Contains

dashboard_screenshots/

Full_Superstore.csv

task2.pbix #(Sales_Dashboard)

README.md (this file)

📬 Contact

For any queries regarding the dashboard or project, feel free to reach out.
