🛒 Zepto Quick-Commerce SQL Data Analysis

📌 Project Overview

This project focuses on analyzing a real-world quick-commerce inventory dataset (Zepto) using PostgreSQL.
The objective was to simulate how data analysts work with messy, unstructured e-commerce data and derive business-relevant insights related to pricing, inventory, stock availability and product performance.

The project covers the end-to-end data analysis workflow - from database setup and exploratory analysis to data cleaning and insight generation using SQL.

🎯 Objectives

- Set up and work with a real-world e-commerce inventory database.

- Understand product distribution, pricing patterns and stock availability.

- Identify and resolve data quality issues.

- Generate business-driven insights using SQL queries.

- Strengthen hands-on skills in PostgreSQL and SQL-based analysis.

🗂 Dataset Overview

The dataset represents Zepto-style quick-commerce inventory data, containing product-level information such as:

- Product name
- Category
- Price (in paise)
- Discounted price
- Stock availability
- Product quantity / weight

As expected in real-world datasets, the data contained:

- Missing values
- Inconsistent pricing formats
- Invalid or unrealistic entries

🛠 Tools & Technologies Used

Database: PostgreSQL

Language: SQL

Concepts:

- Exploratory Data Analysis (EDA)
- Data Cleaning & Validation
- Aggregations and filtering
- Business insight generation

🔍 Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the structure and quality of the data before deeper analysis. Key EDA steps included:

- Analyzing product categories and their distribution
- Checking stock availability across products
- Exploring price ranges to identify anomalies and inconsistencies
- Identifying null values and invalid entries
- Reviewing discount patterns across products

EDA helped highlight data quality issues that needed cleaning before reliable analysis.

🧹 Data Cleaning & Preparation

Based on insights from EDA, multiple data cleaning steps were performed:

- Handled null and missing values to prevent inaccurate analysis
- Removed invalid or inconsistent records
- Converted pricing values from paise to rupees for business readability
- Standardized columns to ensure consistency across queries
- These steps ensured the dataset was analysis-ready and reliable.

📊 SQL Analysis & Business Queries

After cleaning, SQL queries were written to derive meaningful insights, including:

Identifying top-performing and low-performing products

- Analyzing pricing and discount patterns
- Evaluating inventory levels and stock availability
- Understanding category-level distribution
- Assessing potential revenue-impacting factors

The analysis relied on:

- WHERE, ORDER BY, GROUP BY
- Aggregate functions such as COUNT, SUM, and AVG
- Conditional logic for filtering business-relevant data

📈 Key Insights

Some of the high-level insights derived include:

- Clear variation in pricing and discounts across categories
- Identification of products with high price but low stock availability
- Detection of inconsistent pricing entries requiring cleaning
- Visibility into categories contributing most to inventory volume

These insights mirror the kind of analysis useful for pricing, inventory planningand business decision-making.

🚀 Learnings & Takeaways

- Gained hands-on experience working with messy, real-world data
- Strengthened understanding of EDA using SQL
- Learned how data cleaning directly impacts analysis quality
- Improved ability to translate raw data into business-relevant insights
- Built confidence using PostgreSQL for analytical workflows

🔮 Future Improvements

- Extend analysis using joins with sales or order-level data
- Create dashboards using Power BI or Tableau
- Add time-based analysis if historical data is available

