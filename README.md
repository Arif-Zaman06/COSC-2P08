# Coffee Shop Sales Analysis (Team 16)

## Overview
This project analyzes coffee shop transaction data to uncover patterns in revenue, customer behavior, and store performance. The analysis was conducted using Python (Pandas, Matplotlib) as part of a Data Challenge assignment.

The goal is to answer key business questions and provide actionable insights through data cleaning, analysis, and visualization.

---

## Dataset
**File:** `team16_coffeeshop.csv`

The dataset contains transactional records including:
- `time_of_day` – Morning, Afternoon, Evening
- `item_category` – Coffee, Tea, Pastry, Sandwich, etc.
- `size` – Small, Medium, Large
- `price` – Transaction value
- `payment_type` – Cash, Card, Mobile
- `loyalty_member` – TRUE/FALSE
- `location` – Store A, Store B, Store C

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
- Checked structure (`df.info()`)
- Reviewed summary statistics (`df.describe()`)
- Identified missing values

### 3. Data Cleaning
- Converted `price` to numeric format
- Standardized `loyalty_member` values (True/False)
- Filled missing values using mean

### 4. Data Analysis
Used `groupby()` operations to compute:
- Total revenue by time of day
- Average transaction value by category
- Average spending by loyalty membership
- Total sales by location

### 5. Visualization
Created bar charts to visually represent:
- Revenue trends
- Category performance
- Store comparisons

---

## Key Findings

- **Morning generates the highest revenue**, making it the busiest and most profitable time period.
- **Tea and Coffee have the highest average transaction values**, indicating strong revenue contribution from beverages.
- **Loyalty members spend slightly more on average**, suggesting a modest positive impact of the loyalty program.
- **Store A has the highest total sales**, although performance across all stores is relatively similar.

---

## Insights & Business Impact

- Focus staffing and promotions during **morning peak hours**
- Prioritize high-value categories like **coffee and tea**
- Improve loyalty programs to further increase customer spending
- Monitor store performance to identify optimization opportunities

---

## ▶️ How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/coffee-shop-analysis.git
