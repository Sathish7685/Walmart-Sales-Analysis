# Walmart Sales Data Analysis

## Project Overview
This project explores Walmart's sales data to understand top-performing branches, products, and customer behavior. The aim is to analyze sales trends, product performance, and customer segments to enhance sales strategies and optimization.

## Data Source
The dataset is sourced from the Kaggle Walmart Sales Forecasting Competition and contains sales transactions from three Walmart branches located in Mandalay, Yangon, and Naypyitaw. The data includes 17 columns and 1,000 rows.

## Data Columns
- **invoice_id**: Unique sale identifier
- **branch**: Branch where sale occurred
- **city**: City of the branch
- **customer_type**: Type of customer
- **gender**: Gender of the customer
- **product_line**: Product category sold
- **unit_price**: Price per product
- **quantity**: Quantity of products sold
- **VAT**: Sales tax amount
- **total**: Total cost of the sale
- **date**: Transaction date
- **time**: Transaction timestamp
- **payment_method**: Payment amount
- **cogs**: Cost of goods sold
- **gross_margin_percentage**: Margin percentage
- **gross_income**: Gross income
- **rating**: Customer rating

## Analysis Areas
1. **Product Analysis**: Identify top-performing product lines and areas for improvement.
2. **Sales Analysis**: Evaluate sales trends to assess the effectiveness of sales strategies.
3. **Customer Analysis**: Explore customer segments and purchasing patterns.

## Approach
1. **Data Wrangling**: Inspect data for missing values and handle them through appropriate methods.
2. **Database Creation**: Build a database, create tables, and filter out NULL values.
3. **Feature Engineering**: 
   - **Time of Day**: Categorize sales into Morning, Afternoon, and Evening.
   - **Day of Week**: Extract the day of the week for each transaction.
   - **Month of Year**: Extract the month of the year for each transaction.
4. **Exploratory Data Analysis (EDA)**: Analyze the dataset to answer key business questions and draw insights.

## Goals
- Understand the factors affecting sales performance.
- Gain insights to optimize sales strategies for different branches and product lines.
- Analyze customer behavior and segment-based profitability.

## Tools Used
- Python (Pandas, NumPy, Matplotlib)
- SQL (for database management)
- Jupyter Notebooks (for analysis and visualization)

## How to Run
1. Clone this repository.
2. Install necessary dependencies: `pip install -r requirements.txt`.
3. Run the Jupyter Notebook to explore the analysis.
