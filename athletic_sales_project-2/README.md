# Athletic Sales Analysis

## Overview
This project analyzes athletic wear sales data from 2020 and 2021 to uncover key insights about regional performance, retailer sales, and trends in women's athletic footwear. By combining and cleaning datasets, the analysis highlights top-performing cities, retailers, and time periods for athletic sales.

## Objectives
The primary objectives of this project are:
1. To determine which cities and regions in the U.S. sold the most athletic wear.
2. To identify the retailers with the highest total sales for athletic wear.
3. To analyze sales trends specifically for women's athletic footwear, including top-selling retailers, days, and weeks.

## Files in the Repository
- `athletic_sales_analysis.ipynb`: Jupyter Notebook containing the full analysis and code implementation.
- `athletic_sales_2020.csv`: Sales data for 2020.
- `athletic_sales_2021.csv`: Sales data for 2021.

## Key Insights
### 1. Top Cities by Sales and Products Sold
- **Regions with the most products sold**: Insights into cities and regions leading in the number of items sold.
- **Regions with the highest revenue**: Highlights the cities generating the most sales revenue.

### 2. Retailer Performance
- **Retailers with the highest total sales**: Rankings of retailers based on revenue performance across the U.S.
- **Retailers selling the most women's athletic footwear**: Analysis specific to women's footwear sales.

### 3. Time-Based Trends
- **Top days for women's athletic footwear sales**: Identifies the highest-grossing days for this category.
- **Top weeks for women's athletic footwear sales**: Weekly trends providing broader insights into sales patterns.

## Process
The project follows these steps:
1. **Data Import and Cleaning**:
   - Loaded datasets for 2020 and 2021.
   - Combined data while ensuring column consistency and addressing missing values.
   - Converted the `invoice_date` column to a datetime format for temporal analysis.

2. **Analysis by Region**:
   - Grouped data by region, state, and city to identify top-performing locations.

3. **Retailer Analysis**:
   - Grouped sales by retailer and location to determine leading businesses.

4. **Women's Athletic Footwear Trends**:
   - Filtered data for the women's footwear category.
   - Analyzed daily and weekly sales performance for this category.

## How to Run
1. Clone the repository:
   ```bash
   git clone git@github.com:Ryan-ai-champ/athletic_sales_analysis.git
