# Sales & Revenue Analytics

## Project Overview

This project focuses on analyzing retail sales data from the Superstore dataset to understand overall sales performance and identify important patterns in the business.

The project covers the complete analytics process, starting with data inspection and cleaning in Python, followed by exploratory analysis and visualization. The final results are presented in a Tableau dashboard to make the findings easier to understand and communicate.

## Goals

The main goals of this project were to:

- Understand the structure and quality of the sales data.
- Clean and prepare the data for analysis.
- Analyze sales performance across different categories and regions.
- Identify monthly sales trends.
- Find the top-performing products based on sales.
- Present the main findings through clear visualizations and a Tableau dashboard.

## Methods Used

The dataset was first loaded and inspected using Python and Pandas. I checked the dataset structure, data types, missing values, duplicate records, and unique values in important columns.

The data was then cleaned and prepared for analysis. The order and shipping date columns were converted into proper datetime format, missing values were checked, and additional fields such as year, month, month name, and shipping days were created to support the analysis.

Pandas was used for filtering, grouping, aggregation, and calculating the required sales metrics. Matplotlib was used to create visualizations for the exploratory analysis.

Finally, the cleaned data was used in Tableau to create a dashboard containing:

- Total Sales
- Sales by Category
- Sales by Region
- Monthly Sales Trend
- Top 5 Products by Sales

## Key Insights

The analysis showed that the business generated approximately **$2.26 million in total sales**.

- **Technology** was the highest-selling category with approximately **$827K** in sales.
- **Furniture** generated approximately **$729K** in sales.
- **Office Supplies** generated approximately **$705K** in sales.
- The **West** region had the highest sales at approximately **$710K**.
- The **East** region followed with approximately **$670K**.
- The **Central** and **South** regions generated approximately **$493K** and **$389K** respectively.
- Sales varied considerably from month to month, with several noticeable peaks and lower-performing periods.
- The **Canon imageCLASS 2200 Advanced Copier** was the top-performing product by total sales, generating approximately **$61.6K**.

These findings help highlight which categories, regions, products, and time periods contributed most to overall sales.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Tableau
- Jupyter Notebook
- Git & GitHub

## Project Files

- `superstore.csv` - Original Superstore dataset.
- `superstore_cleaned.csv` - Cleaned and transformed dataset used for analysis.
- `sales-revenue-analysis.ipynb` - Python notebook containing the data inspection, cleaning, analysis and visualizations.
- `sales-revenue-analysis.twbx` - Packaged Tableau workbook containing the dashboard.
