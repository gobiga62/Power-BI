# Power-BI

# Sales Data Analysis Dashboards

This repository contains two Power BI dashboards analyzing sales data for **Walmart Sales** and **Kevin Cookie Company**. These dashboards provide insights into key performance metrics and trends, aiding strategic decision-making. Each dashboard leverages SQL for data preprocessing, Power BI for interactive visualizations, and addresses specific business inquiries about product performance, customer demographics, and sales trends.

---

## Kevin Cookie Company Sales Dashboard

### Project Aim
The Kevin Cookie Company dashboard provides a comprehensive view of:
- Monthly sales and profit trends.
- Performance of top products.
- Key customer insights across different states.

### Dataset Description
This dataset captures cookie sales, revenue, and customer details across various U.S. states for the years 2018-2019.

### Process of Analysis
1. **Data Import & Cleaning**: Loaded data into Power BI and conducted necessary data cleaning.
2. **Visualization Setup**: Designed visuals including stacked column, line, and donut charts to analyze different aspects of sales performance.

### Key Insights and Visualizations
- **Total Cost & Profit**: A stacked column chart highlights monthly total costs and profits.
- **Revenue Trends**: A line chart displays monthly revenue trends for a comprehensive view of growth over time.
- **Product Performance**: A donut chart showcases average revenue per cookie type.
- **Top Products & Customers**:
  - Top three products by cookies sold and profit earned.
  - Key customer states based on cookie sales and profit, aiding in targeted marketing strategies.

---

## Walmart Sales Dashboard

### Project Aim
The Walmart Sales dashboard aims to:
- Identify top-performing branches and products.
- Analyze sales trends and customer behavior.
- Streamline sales strategies by examining factors affecting sales across branches over time.

### Dataset Description
The dataset includes sales transactions from three Walmart branches located in Mandalay, Yangon, and Naypyitaw. It contains 17 columns and 1000 rows of data in CSV format.

### Process of Analysis
1. **Data Import & Cleaning**: Imported the dataset into MySQL and conducted data cleaning.
2. **Database Setup**: Created a `salesdatawalmart` database and stored the data in a `sales` table.
3. **Data Preprocessing**: Identified missing values and handled them appropriately. Added columns `time_of_day`, `day_name`, and `month_name` to enrich analysis.
4. **Power BI Integration**: Connected the MySQL database to Power BI and created an interactive dashboard.

### Key Business Inquiries
- **Product Analysis**:
  - Identify top-selling products by total sales, revenue, gross margin %, and rating.
  - Assess if actual sales exceed average sales.
  - Analyze revenue trends by month, day, and time.
- **Customer Insights**:
  - Determine contributions to sales by customer type and gender.
  - Examine gender distribution by branch and identify popular products for each gender.
- **City & Branch Performance**:
  - Identify the highest-selling cities based on total sales and revenue.
  - Analyze ratings by day of the week, month, and time of day.
- **Additional Factors**:
  - Explore the impact of seasonal changes, holidays, economic conditions, and technological shifts on sales.

## Viewing the Dashboards

Both dashboards were designed in Power BI, providing interactive insights. Due to file format limitations, please download and open the `.pbix` files in Power BI for full functionality.

### Thank You!

These dashboards demonstrate my ability to conduct in-depth data analysis and create actionable insights through visualization. They offer a blend of SQL-based data preprocessing, Power BI visualization, and business acumen, making them ideal for presenting to recruiters as examples of my analytical and technical skills.
