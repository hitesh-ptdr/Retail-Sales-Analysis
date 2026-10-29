# Retail Sales Analysis

## Project Overview
This project analyzes retail sales data using Python and Power BI to understand sales performance, product category trends, customer demographics, and purchasing patterns.

## Tools & Technologies
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Microsoft Power BI
- CSV Dataset

## Dataset
The dataset contains 1,000 retail transactions with information about transaction date, customer ID, gender, age, product category, quantity, price per unit, and total amount.

## Data Cleaning
- Checked missing values and duplicate records.
- Verified total amount calculations using quantity and price per unit.
- Created Month and Year columns for time-based analysis.
- Exported the cleaned dataset for Power BI.

## Key Metrics
- **Total Sales:** ₹456,000
- **Total Units Sold:** 2,514
- **Total Transactions:** 1,000
- **Unique Customers:** 1,000

## Key Findings
- Electronics generated the highest category sales at ₹156,905.
- Clothing generated ₹155,580 in sales.
- Beauty generated ₹143,515 in sales.
- Female customers accounted for ₹232,840 in sales.
- Male customers accounted for ₹223,160 in sales.
- May 2023 recorded the highest monthly sales among the full months analyzed.

## Visualizations
### Python Analysis
The Jupyter Notebook includes charts for:
- Sales by product category
- Monthly sales trends
- Sales by gender
- Sales by gender and product category
- Quantity sold by category
- Customer age distribution

### Power BI Dashboard
The interactive dashboard includes:
- KPI cards for sales, quantity, transactions, and customers
- Product category sales comparison
- Monthly sales trend
- Gender-based sales analysis
- Gender and product category comparison
- Quantity sold by product category
- Slicers for Year, Month, Gender, and Product Category

## Project Structure
```text
Retail-sales/
├── charts/
├── data/
│   ├── retail_sales_cleaned.csv
│   └── retail_sales_dataset.csv
├── notebooks/
│   └── Retail_sales.ipynb
├── Retail_Sales_Analysis.pbix
└── README.md
```

## Conclusion
This project demonstrates how Python can be used for data cleaning and exploratory data analysis, while Power BI provides an interactive dashboard for exploring retail sales performance and customer purchasing patterns.

## Author
Hitesh Patidar
