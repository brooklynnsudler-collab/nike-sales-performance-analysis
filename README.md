# nike-sales-performance-analysis
## **Nike Sales Performance Analysis**
Data analytics project exploring sales performance, product trends, revenue patterns, and reported profitability using Python, SQL, and Microsoft Power BI.

**Project Overview**\
With this project, I wanted to transform a raw sales dataset into meaningful business insights through data cleaning, data analysis, SQL querying, and interactive dashboard development. To present my findings, I created a final Power BI dashboard that provides an overview of sales performance across product lines, sales channels, regions, and gender categories from 2023-2025.

**Tools & Technologies**
- Python: Data cleaning and exploratory data analysis
- pandas: Data manipulation and transformation
- SQL: Data querying, aggregation, filtering, and business analysis
- Power BI: Dashboard development and data visualization

**Project Workflow**
1. Data Cleaning & Preparation -- Python
   - Inspected the original dataset and evaluated data quality
   - Identified missing values and duplicate records.
   - Investigated unusual values.
   - Converted order dates into appropriate datetime formats.
   - Exported the cleaned dataset for further analysis.

2. Exploratory Data Analysis -- Python
   - Product line distributions.
   - Regional sales distributions.
   - Discount patterns.
   - Missing sales information.
   - Revenue and profit distributions.

3. Business Analysis -- SQL
   Used SQL to investigate business questions involving:
   - Record counts by product line.
   - Total revenue by sales channel.
   - Average profit by gender category.
   - Highest-revenue product lines.
   - Regional revenue performance.
   - Product profitability comparisons.
   
   Applied SQL concepts including:
   SELECT, WHERE, GROUP BY, ORDER BY, HAVING, CASE WHEN.

4. Dashboard Development -- Power BI
   Developed an interactive sales performance dashboard featuring:
   - KPI cards
   - Total revenue by product line.
   - Average reported profit line.
   - Total revenue by sales channel.
   - Monthly revenue trends.
   - Total revenue by region.
   - Revenue and profit comparisons by product line.
   - Average reported profit by gender category.
   - Interacted slicers.

**Data Quality & Limitations**\
The original dataset contained many missing and zero-valued sales information. During the analysis, the Profit field contained values that could not be reconciled with recorded Revenue. For this reason, profit-related metrics are identified as reported profit, while recorded revenue also reflects using only the values present in the source dataset. Therefore, the analysis does not necessarily represent complete sales revenue nor profit.

**Key Findings**
- Training was shown to have generated the highest recorded revenue of the five product lines.
- Online sales generated more recorded revenue than retail sales.
- Kolkata had the highest recorded regional revenue.
- Women had the highest average reported profit among the gender categories.


