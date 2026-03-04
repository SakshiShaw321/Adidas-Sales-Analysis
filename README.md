# Adidas-Sales-Analysis using Python + Power BI
📘 Project Overview
This project provides a comprehensive analysis of Adidas sales data to uncover business performance insights and identify growth opportunities. Using Python for data preprocessing and Power BI for dashboard visualization, the analysis explores key dimensions such as regional performance, profit margins, product trends, and customer segments.

🧩 Objectives
Analyze sales and profit performance by product, city, and region.

Identify top-performing categories and products.

Understand customer behavior across gender and regions.

Deliver interactive dashboards to support strategic business decisions.

🛠️ Tools & Technologies Used
Python: Data Cleaning, Transformation & Exploratory Data Analysis

Libraries: pandas, matplotlib, seaborn, numpy

Power BI: Data Modeling, KPI Design, and Dashboard Creation

Excel / CSV: Data Source

GitHub: Project Documentation & Version Control

🧮 Python Analysis Highlights
Key analytical steps performed in Python:

Total Revenue by Product Category
revenue_by_category = df.groupby('Product Category')['Total Sales'].sum().reset_index()

Top 10 Cities by Total Revenue
top_cities = df.groupby('City')['Total Sales'].sum().reset_index().sort_values(by='Total Sales', ascending=False).head(10)

Profit Trend Over Time
profit_trend = df.groupby('Year-Month')['Operating Profit'].sum().reset_index()
📊 Visualizations in Python
Total Revenue by Product Category (Pie Chart)

Top Performing Cities (Barh Plot)

Sales & Profit Trend (Line Chart)

Gender-wise Sales Distribution

📈 Power BI Dashboard Highlights
KPIs:
💰 Total Sales

📈 Total Profit

🏷️ Average Selling Price

🛒 Total Transactions

Visuals:
Sales & Profit Trend (Line Chart)

Top Products by Sales (Bar Chart)

Sales by Category (Donut Chart)

-Sales by Region & City (Map Visual)

-Gender-based Sales Distribution

📸 Dashboard Preview:
🌏Overview
🗺️Regional Analysis
🧩Product Analysis
🏬Retailer Analysis
💳Sales Method Analysis

💡 Key Insights
The West region generated the highest revenue and profit contribution.

Men’s Footwear was the top-performing category across all regions.

Q3 recorded strong sales momentum, indicating seasonal peaks.

Top 5 cities accounted for nearly 40% of total sales revenue.

Profit margins were highest in Accessories compared to Apparel.

💼 Business Impact
Helped identify high-performing regions for strategic marketing investments.

Guided inventory management by pinpointing fast-moving products.

Enabled data-driven pricing and discount strategies through sales trend insights.

Enhanced profitability forecasting by visualizing quarterly sales patterns.

Supported decision-makers with real-time Power BI dashboards to track KPIs and improve business agility.

🚀 Outcome
This analysis empowered Adidas decision-makers to:

Optimize regional sales performance through targeted campaigns.

Improve inventory turnover by aligning stock with demand trends.

Increase profit margins by focusing on top categories and cities.

Strengthen data-driven decision-making culture across teams.



