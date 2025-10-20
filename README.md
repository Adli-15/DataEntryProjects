# DataEntryProjects
This is my personal projects

OBJECTIVE:
-Identify and correct column name inconsistencies.
-Remove special symbols and formatting errors from numerical data.
-Convert financial figures from text to numeric types.
-Validate data integrity and accuracy after cleaning.
-Generate visual insights on company sales and profit performance.

DATA SOURCE:
https://www.kaggle.com/datasets/atharvaarya25/financials


TOOLS USED:
Microsoft Excel

PROCESS:
1. Data Understanding
-Imported the Company Financials Dataset containing sales and profit information categorized by segment, country, and time period.
-Identified initial issues such as inconsistent column names, symbols in numeric data (e.g., $, ,, -), and mixed data types.
-Reviewed column meanings: Sales, Profit, COGS, Discount, Segment, and Date-related columns.

2. Data Cleaning & Preprocessing
-Renamed and standardized column names (removed extra spaces and unified formatting).
-Removed unwanted symbols like $, commas ,, and hyphens - from numeric fields.
-Converted data types from object/string to numeric (int/float) for calculations.
-Handled missing or invalid values (e.g., replaced '-' with 0 where appropriate).
-Validated numeric accuracy by ensuring totals (e.g., Gross Sales = Units Sold × Sale Price) matched.
-Trimmed whitespace and corrected inconsistent entries (e.g., “ June ” → “June”).

3. Exploratory Data Analysis (EDA)
-Explored key financial metrics such as Sales, Profit, and Discounts.
-Conducted descriptive statistics to summarize average, minimum, and maximum values for each numerical column.
-Analyzed distribution of Sales and Profit using histograms and box plots to detect outliers and spread.

4. Descriptive Statistics & Pivot Analysis
-Used Pivot Tables to summarize:
-Total and average Sales and Profit by Segment and Country.
-Yearly and monthly Sales trends.
-Calculated KPIs such as:
-Average profit margin per market segment.
-Total discounts applied across regions.
-Sales-to-COGS ratio.

5. Data Visualization
-Visualized Sales distributions using histograms to understand data skewness.
-Created monthly sales trend line charts to show seasonality or growth patterns.
-Designed box plots of Sales values to highlight variation and outliers.
-Visualized Total Sales per Segment with bar charts for easy comparison.
-Explored the relationship between Discount and Profit using scatter plots to understand their correlation.

6. Insights & Interpretation
-Found key patterns and relationships (e.g., which segment has the highest profit, how discounts affect profitability, which months have peak sales).
-Highlighted actionable insights for financial decision-making and reporting.

OUTPUT:

PROJECT SUMMARY:
This project focuses on cleaning, validating, and preparing a raw company financial dataset for analysis. The dataset contains sales and profit data categorized by market segment and region, but includes multiple formatting issues such as inconsistent column names, currency symbols, negative signs, and comma-separated numerical values.

As a data entry and finance specialist, the goal of this project was to transform messy and unstructured financial data into a clean, standardized format suitable for accurate reporting and analysis. The project involved identifying and correcting column name errors, removing unwanted symbols (e.g., “$”, “-”, “,”), converting data types from text to numeric values, and validating totals to ensure data accuracy.

After cleaning, exploratory data analysis (EDA) was conducted to visualize trends in sales and profit across time and market segments. The final dataset provides a reliable foundation for financial reporting, decision-making, and performance evaluation.
