# Blinlit-Analysis
This is a comprehensive retail analytics project that analyzes Blinkit's grocery sales data using both Power BI for visualization and Python for predictive modeling. The project demonstrates end-to-end data analytics capabilities from data preparation to actionable business insights.
Project Overview
The analysis focuses on understanding Blinkit's sales performance across multiple dimensions including product categories, outlet characteristics, customer ratings, and regional distribution. It combines descriptive analytics with machine learning to provide both historical insights and predictive capabilities.
Key Components
1. Data Analysis & Visualization (Power BI)

Data Preparation: Raw grocery sales data was cleaned in Power Query, with standardized column names and proper data type formatting
Data Modeling: Implemented a star schema architecture with fact tables (Sales) and dimension tables (Items, Outlets, Categories)
DAX Measures: Created custom KPIs including Total Sales, Average Rating, Average Item Weight, and Discount Impact
Interactive Dashboard: Built with slicers for dynamic filtering by Outlet Size, Item Type, and Location

2. Machine Learning Component (Python)

Exploratory Data Analysis: Distribution analysis, correlation studies, and feature relationships
Predictive Modeling: Random Forest Regressor to predict sales based on various features
Feature Engineering: Preprocessing pipeline with imputation, scaling, and one-hot encoding
Model Evaluation: Performance measured using R² Score and RMSE metrics

# Business Insights Discovered
Outlet Performance:

Medium-sized outlets outperform small and large ones
Supermarket Type 1 outlets are the strongest sales contributors
Established outlets (more years in operation) show consistently higher performance

Product Preferences:

Fruits & Vegetables and Snack Foods dominate sales
Regular fat content items outsell Low Fat products
Health/hygiene products show growth potential

Customer Satisfaction:

Majority of products receive 4-5 star ratings
High ratings indicate strong product acceptance and customer trust

Technical Skills Demonstrated

Power BI: Data transformation, star schema modeling, DAX calculations, interactive visualizations
Python Libraries: Pandas, Matplotlib, Seaborn, Scikit-learn
Data Science: EDA, feature engineering, pipeline creation, model evaluation
Business Intelligence: KPI development, dashboard design, actionable insight generation
