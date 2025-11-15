# Customer Shopping Behavior Analysis

End-to-End Data Analytics Project (Python • SQL • Power BI)
This project delivers a complete, industry-style data analysis workflow using Python, PostgreSQL, and Power BI to explore customer shopping behavior across 3,900 transactions. It focuses on uncovering spending patterns, product preferences, customer groups, and subscription behavior—similar to what analysts do in a retail/e-commerce environment.
________________________________________
# 📊 1. Project Overview
The goal of this project is to identify key shopping insights that help businesses make informed decisions. The analysis covers:
•	Customer demographics
•	Purchasing patterns
•	Discount usage
•	Product performance
•	Subscription behavior
•	Seasonal and category-level trends
________________________________________
# 🗂 2. Dataset Summary
•	Rows: 3,900
•	Columns: 18
•	Key Features:
o	Demographics: age, gender, location, subscription status
o	Purchase details: item, category, amount, size, color, season
o	Behavior patterns: review ratings, shipping type, previous purchases, discount usage
•	Missing Values: 37 missing review ratings (filled using category-wise median)
________________________________________
# 🧹 3. Data Cleaning & Feature Engineering (Python)
The dataset was cleaned and preprocessed using Python:
•	Loaded and explored data using pandas
•	Filled missing ratings using category-specific median imputation
•	Standardized all column names to snake_case
•	Dropped redundant fields after checking for overlap
•	Created age_group using binning
•	Engineered purchase_frequency_days from purchase history
•	Inserted cleaned dataset into PostgreSQL for further analysis
________________________________________
# 🧠 4. Business Analysis Using SQL
SQL queries were developed to answer realistic business questions:
•	Revenue comparison by gender and age group
•	High-spending customers using discounts
•	Best and worst-rated products
•	Standard vs. Express shipping behavior
•	Subscribers vs. non-subscribers spending patterns
•	Product categories most driven by discounts
•	Customer segmentation: New, Returning, Loyal
•	Top products within each category
•	Relationship between repeat purchases and subscription likelihood
These insights form the foundation for actionable strategic decisions.
________________________________________
# 📈 5. Power BI Dashboard
A multi-page Power BI dashboard visualizes:
•	Overall sales & customer metrics
•	Product and category performance
•	Customer demographics and purchase patterns
•	Review ratings & subscription trends
The dashboard helps stakeholders quickly understand trends and make data-driven decisions.
________________________________________
# 💡 6. Key Business Recommendations
•	Target high-value customer groups through tailored marketing campaigns
•	Strengthen loyalty programs to convert returning buyers into loyal customers
•	Boost subscription conversion by promoting key benefits
•	Optimize discount strategy to support sales while preserving profit
•	Highlight high-rated products across marketing and online channels
________________________________________
# 🛠 Tech Stack
•	Python: pandas, numpy, matplotlib
•	SQL: PostgreSQL
•	Power BI
•	Data cleaning, feature engineering, descriptive analysis, visualization



<img width="4872" height="2656" alt="project_plan" src="https://github.com/user-attachments/assets/7bdbaf81-1c9a-4752-85a0-bad840be8a37" />
