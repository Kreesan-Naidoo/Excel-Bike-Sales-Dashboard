# Excel Bike Sales Dashboard
-- Project Overview \
This project transforms 1,000 records of raw bike sales data into a clean, interactive dashboard using Microsoft Excel. The goal was to practise the full analyst workflow — from raw data and cleaning through to a polished, filterable dashboard that communicates sales insights at a glance.

-- Tools & Features Used

Microsoft Excel\
Data Cleaning & Preparation\
Pivot Tables\
Pivot Charts\
Slicers (interactive filters)\
Dashboard layout and design


-- Dataset

Records: 1,000 rows of bike sales transaction data\
Key fields include: Customer demographics (age, gender, marital status, income), region, commute distance, education level, and whether a bike was purchased


-- Project Workflow
1. Data Cleaning
Before any analysis, the raw dataset was cleaned and prepared:

Removed duplicate records
Standardised categorical values for consistency (e.g. gender, marital status abbreviations expanded to full words)
Checked for and handled blank or null values
Created a working copy of the raw data to preserve the original dataset

2. Data Preparation — Age Bracketing
A new calculated column was added to group customers into meaningful age brackets (e.g. Adolescent, Middle Age, Old) using nested IF statements — making the data more suitable for visual grouping in charts.
3. Pivot Tables
Multiple pivot tables were built to summarise the data across different dimensions:

-Average income by gender and bike purchase status — to identify income patterns between buyers and non-buyers\
-Customer count by commute distance and purchase status — to explore whether proximity influences buying behaviour\
-Customer count by age bracket and purchase status — to understand which age groups are most likely to purchase

4. Pivot Charts
Each pivot table was visualised with an appropriate chart type, chosen to best represent the underlying data pattern — bar charts for comparisons, line charts for distributions across ranges.
5. Interactive Dashboard with Slicers

All charts were brought together on a single Dashboard sheet and connected to Slicers for interactive filtering by:

-Marital Status\
-Region\
-Education Level

This allows a user to filter the entire dashboard simultaneously with one click — replicating the kind of self-service reporting used in real business environments.


-- Key Insights from the Dashboard

Customers with higher average incomes were more likely to purchase a bike, across both genders\
Middle-aged customers represented the largest group of bike purchasers\
Customers with a short commute distance (0–1 miles) showed the highest purchase rates, suggesting bikes are favoured for short-distance travel\
Regional and education filters allow stakeholders to drill into specific customer segments interactively\
