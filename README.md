# Coffee Shop Sales Analysis (Team 16)

## Overview
This project analyzes coffee shop transaction data to uncover patterns in revenue, customer behavior, and store performance. The analysis was conducted using Python (Pandas, Matplotlib) as part of a Data Challenge assignment.

The goal is to answer key business questions and provide actionable insights through data cleaning, analysis, and visualization.

---

## Dataset
File: `team16_coffeeshop.csv`

The dataset contains transactional records including:
- time_of_day – Morning, Afternoon, Evening
- item_category – Coffee, Tea, Pastry, Sandwich, etc.
- size – Small, Medium, Large
- price – Transaction value
- payment_type – Cash, Card, Mobile
- loyalty_member – TRUE/FALSE
- location – Store A, Store B, Store C

---

## Objectives
This project answers the following questions:

1. Which time of day generates the most revenue?
2. What is the average transaction value by item category?
3. Do loyalty members spend more on average?
4. Which location has the highest sales?

---

## Tools & Technologies
- Python
- Pandas (data manipulation)
- Matplotlib (visualization)
- Jupyter Notebook / Google Colab

---

## Project Workflow

### 1. Data Loading
The dataset is loaded into a Pandas DataFrame for analysis.

### 2. Data Exploration
- Checked structure (df.info())
- Reviewed summary statistics (df.describe())
- Identified missing values

### 3. Data Cleaning
- Converted price to numeric format to ensure accurate calculations
- Standardized loyalty_member values (TRUE/FALSE) into consistent boolean format
- Filled missing values in price using the mean to maintain dataset completeness
- Verified that no invalid or unrealistic values (such as negative prices) were present

### 4. Data Analysis
Used groupby operations to compute:
- Total revenue by time of day
- Average transaction value by category
- Average spending by loyalty membership
- Total sales by location

### 5. Visualization
Created bar charts to represent:
- Revenue trends
- Category performance
- Store comparisons

---

## Key Findings

- Morning generates the highest revenue at 2298.87, making it the busiest and most profitable time period.
- Tea and coffee have the highest average transaction values (3.47 and 3.43), indicating strong revenue contribution from beverages.
- Loyalty members spend slightly more on average (3.36) than non-members (3.32), showing a small positive impact of the loyalty program.
- Store A has the highest total sales at 1602.73, although performance across all stores is relatively similar.

---

## Insights & Business Impact

- Focus staffing and promotions during morning peak hours
- Prioritize high-value categories such as coffee and tea
- Improve loyalty programs to further increase customer spending
- Monitor store performance to identify optimization opportunities

---

## How to Run the Project

1. Clone this repository:
   git clone https://github.com/your-username/coffee-shop-analysis.git

2. Open the project in Jupyter Notebook or Google Colab

3. Upload the dataset (team16_coffeeshop.csv)

4. Run all cells to reproduce the analysis and visualizations

---

## Repository Structure

coffee-shop-analysis/
│
├── Data Challenge.ipynb   # Main notebook
├── team16_coffeeshop.csv # Dataset
├── README.md             # Documentation

---

## Conclusion

This project analyzed coffee shop sales data to identify key revenue patterns and customer behaviors. The results show that morning hours drive the highest revenue, beverage categories contribute the most value, and loyalty programs have a small positive impact on spending.

Overall, these insights can support better operational decisions, improve marketing strategies, and enhance customer engagement.
