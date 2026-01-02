Electric Car Sales Analysis Repo
This repository demonstrates a complete data analysis pipeline for electric car sales data, transforming raw dirty data into cleaned dataset and culminating in an interactive dashboard. The project uses Excel files to explore factors influencing electric car purchases, such as demographics, income, and commute distance.
​

Data Sources
Raw data resides in "Electric-car-sales-dataset.xlsx", featuring columns like id, martialstatus, gender, income, children, education, occupation, homeowner, cars, commutedistance, region, age, agecategory, and purchasedelectriccar. Snippets reveal inconsistencies like varying capitalization in "martialstatus" (likely "marital status"), "commutedistance" spellings ("0-1 miles" vs "0-1 Miles"), and "More then 10 Miles".
​

Cleaned version in "Data-cleaned.xlsx" standardizes these fields for analysis, maintaining the same structure but with consistent formatting across entries.
​

Cleaning Process
Dirty data shows issues including inconsistent spacing in income ("40,000"), lowercase/uppercase variations in categorical fields (e.g., "Partial College", "High School"), and minor typos like "More then" instead of "More than".
​

Cleaning likely involved standardizing text cases, removing extra spaces, correcting typos, and ensuring uniform comma formatting in numerics, resulting in a reliable dataset ready for visualization.
​

Dashboard Insights
"Electric-sales-Dashboard.xlsx" summarizes key metrics from cleaned data, including average income by gender and purchase status (e.g., No: Female $73,333, Male $69,000; Yes: Female $39,000, Male $50,000).
​

Visuals cover electric car sales by age category (e.g., No: Middle Age 11, Old 4, Young 1; Yes: Middle Age 14, Old 2, Young 1) and commute distance breakdowns.
