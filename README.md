# sales_profit_analysis_python
Sales and Profit Analysis using Python, Pandas, NumPy, Matplotlib and EDA techniques.

# Sales & Profit Analysis using Python

## Project Overview

This project analyzes sales and profit data using Python and Exploratory Data Analysis (EDA) techniques. The objective is to identify sales trends, regional performance, customer behavior, category performance, and profit-generating opportunities.

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Dataset Information

The dataset contains:

- Order ID
- Order Date
- Ship Date
- Region
- State
- Category
- Sub Category
- Customer Name
- Segment
- Sales
- Quantity
- Discount
- Profit

### Dataset Size
- Total Records: 800
- Total Columns: 13

---

## Data Cleaning & Preparation

The following data preparation steps were performed:

- Examined dataset structure using `df.info()`
- Generated descriptive statistics using `df.describe()`
- Checked for missing values
- Checked for duplicate records
- Converted Order Date and Ship Date to datetime format
- Created Fiscal Year column
- Created Fiscal Quarter column
- Created Month column for time-series analysis

### Data Quality Results

- Missing Values: 0
- Duplicate Records: 0

---

## Key Performance Indicators (KPIs)

| KPI | Value |
|------|--------|
| Total Sales | 4.08 Million |
| Total Profit | 1.00 Million |
| Total Orders | 800 |
| Average Order Value | 5,099 |

---

## Analysis Performed

### 1. Region-wise Sales Analysis
Analyzed sales performance across Central, East, South, and West regions.

### 2. Category-wise Sales Analysis
Compared sales contribution across Furniture, Technology, and Office Supplies categories.

### 3. Segment-wise Sales Analysis
Compared Consumer, Corporate, and Home Office customer segments.

### 4. Top Customer Analysis
Identified customers generating the highest sales revenue.

### 5. Monthly Sales Trend Analysis
Evaluated monthly sales patterns and seasonal fluctuations.

### 6. Region-wise Profit Analysis
Compared profitability across different regions.

### 7. Category-wise Profit Analysis
Identified categories generating the highest profit.

### 8. Discount vs Profit Analysis
Explored the relationship between discount levels and profitability.

---

## Business Insights

- South region generated the highest sales of **1.22 Million**, followed by East (**0.98 Million**), West (**0.95 Million**), and Central (**0.93 Million**).

- South region also achieved the highest profit of **266K**, while Central recorded the lowest profit of **230K**.

- Office Supplies was the top-performing category with **1.38 Million** sales and **351K** profit.

- Technology generated **1.36 Million** sales and **323K** profit.

- Furniture contributed **1.34 Million** sales and **330K** profit.

- Consumer segment generated the highest sales of **1.59 Million**, followed by Home Office (**1.26 Million**) and Corporate (**1.23 Million**).

- Meena was the highest-value customer, contributing **771K** in total sales.

- Monthly sales peaked at approximately **193K** during the analysis period.

- Total sales reached **4.08 Million** with a total profit of **1.00 Million** across **800 orders**.

- The average order value was approximately **5.1K** per order.

- Discount and profit showed no strong positive relationship, indicating that higher discounts did not consistently increase profitability.

---

## Visualizations Included

- Data Overview
- KPI Summary
- Region-wise Sales Analysis
- Category-wise Sales Analysis
- Segment-wise Sales Analysis
- Top Customer Analysis
- Monthly Sales Trend Analysis
- Region-wise Profit Analysis
- Category-wise Profit Analysis
- Discount vs Profit Scatter Plot

---

## Repository Structure

```text
sales_profit_analysis_python/
│
├── README.md
├── Sales_Profit_Analysis_Python.ipynb
└── Screenshots/
```

---

## Future Improvements

- Interactive dashboard using Power BI
- Advanced customer segmentation
- Sales forecasting using machine learning
- Profitability prediction models
- Customer churn analysis

---

## Author

**Bhuvaneswari**

Aspiring Data Analyst

### Skills
- SQL
- Python
- Power BI
- Excel
- Pandas
- NumPy
- Matplotlib
- Data Analysis
- Exploratory Data Analysis (EDA)

## Project Screenshots

### Data Overview
![Data Overview](Screenshots/Data%20overview.png)

### KPI Summary
![KPI Summary](Screenshots/KPI%20Summary.png)

### Region-wise Sales Analysis
![Region-wise Sales Analysis](Screenshots/Region-wise%20sales%20analysis(bar%20chart).png)

### Category-wise Sales Analysis
![Category-wise Sales Analysis](Screenshots/Category-wise%20sales%20analysis(bar%20chart).png)

### Segment-wise Sales Analysis
![Segment-wise Sales Analysis](Screenshots/Segment-wise%20Sales%20Analysis%20(bar%20chart).png)

### Top Customers Analysis
![Top Customers Analysis](Screenshots/Top%20customers%20analysis%20(bar%20chart).png)

### Monthly Sales Trend Analysis
![Monthly Sales Trend Analysis](Screenshots/Monthly%20Sales%20Analysis%20(line%20chart).png)

### Region-wise Profit Analysis
![Region-wise Profit Analysis](Screenshots/Profit%20by%20Region%20(bar%20chart).png)

### Category-wise Profit Analysis
![Category-wise Profit Analysis](Screenshots/Category-wise%20Profit%20analysis%20(bar%20chart).png)
