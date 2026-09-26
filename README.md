# 📊 Sales Data Analysis

> A beginner-friendly end-to-end data analytics project using SQL, Python, Pandas, Matplotlib and Seaborn.

---

## 📌 Project Overview

This project analyzes sales data to understand revenue performance, product performance, customer spending, city-wise sales and category-wise sales.

The project follows a practical data analytics workflow:

**SQL → Data Analysis → Python/Pandas → Visualization → Heatmaps → Business Insights**

---

## 🎯 Project Objectives

- Analyze total sales and revenue
- Identify top-performing products
- Analyze city-wise revenue
- Analyze category-wise revenue
- Identify high-value customers
- Calculate average order value
- Perform exploratory data analysis
- Create business-oriented visualizations
- Create revenue and quantity heatmaps
- Generate useful business insights

---

## 🛠️ Technologies & Tools

| Technology | Purpose |
|---|---|
| MySQL | Data storage and SQL analysis |
| Python | Data analysis |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |
| Seaborn | Advanced visualization and heatmaps |
| Jupyter Notebook | Analysis and experimentation |
| GitHub | Project version control and portfolio |

---

## 📂 Project Structure

```text
sales-data-analysis/
│
├── README.md
├── sales_data.csv
├── sales_analysis.py
├── sales_analysis.ipynb
│
└── images/
    ├── product_revenue.png
    ├── city_revenue.png
    ├── category_revenue.png
    ├── revenue_heatmap.png
    ├── quantity_heatmap.png
    ├── top_products.png
    └── top_customers.png
🔍 SQL Analysis
The following SQL analyses were performed:
- Total number of sales records
- Total revenue
- Total quantity sold
- Average order value
- Product-wise revenue
- City-wise revenue
- Category-wise revenue
- Customer-wise revenue
- Product-wise quantity analysis
Example SQL Query
SELECT
    product,
    SUM(quantity) AS total_quantity,
    SUM(quantity * price) AS total_revenue
FROM sales
GROUP BY product
ORDER BY total_revenue DESC;

🐍 Python Analysis
Python and Pandas were used for:
- Loading the CSV dataset
- Checking data information
- Checking missing values
- Checking duplicate records
- Creating the revenue column
- Group-by analysis
- Product analysis
- City analysis
- Category analysis
- Customer analysis
Revenue Calculation
df["revenue"] = df["quantity"] * df["price"]


📊 Visualizations
Product-wise Revenue
 
City-wise Revenue
 
Category-wise Revenue
 
🔥 Revenue Heatmap
The revenue heatmap shows the relationship between cities and product categories.
 
🔥 Quantity Heatmap
The quantity heatmap shows the number of products sold across different cities and categories.
 
🏆 Top Products
 
👤 Top Customers
 
💡 Business Insights
The project can be used to identify:
- Highest revenue-generating product
- Highest revenue-generating city
- Highest revenue-generating category
- Highest-value customer
- Total revenue generated
- Total quantity sold
- Average order value
- Sales patterns across cities and categories
Note: The exact values are calculated directly from the project dataset.

📈 Project Workflow
Raw Sales Data
      ↓
MySQL Database
      ↓
SQL Analysis
      ↓
CSV Dataset
      ↓
Python + Pandas
      ↓
Data Cleaning & EDA
      ↓
Matplotlib + Seaborn
      ↓
Charts & Heatmaps
      ↓
Business Insights

🚀 Skills Demonstrated
- SQL
- MySQL
- Python
- Pandas
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Data Visualization
- Matplotlib
- Seaborn
- Heatmap Analysis
- Business Insights
- GitHub
👨‍💻 Author
Sonu Shukla
BCA Student | Aspiring Data Analyst
⭐ Project Status
Completed
This is my first portfolio project in Data Analytics, created to demonstrate practical skills in SQL, Python and data visualization.
