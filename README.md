# Sales Forecasting for Rossmann Pharmaceuticals

## Business Need

As a Machine Learning Engineer at Rossmann Pharmaceuticals, the finance team has tasked us with forecasting sales across various stores in different cities for six weeks ahead. Store managers currently rely on personal judgment and experience, but with available data on promotions, competition, holidays, and locality, we aim to build a data-driven solution to predict sales more accurately.

## Task 1 - Exploration of Customer Purchasing Behavior

Exploratory Data Analysis (EDA) is crucial in understanding customer purchasing behavior and factors influencing sales. In this task, we focus on exploring the effects of promotions, store openings, holidays, and competition on sales across different stores. This exploration involves checking data distributions, feature interactions, and correlations with sales. The findings will provide insights into customer behavior and help guide sales forecasting.

## Exploratory Data Analysis (EDA)

The EDA notebook examines all available features, investigating interactions and their effects on the target variable (sales). Our analysis answers key questions such as:
- Distribution of promotions in training and test sets
- Sales behavior before, during, and after holidays
- Seasonal purchase patterns (e.g., Christmas, Easter)
- Correlation between sales and customers
- The impact of promotions on customer attraction and retention

## Data Cleaning and Visualization

To ensure the analysis is accurate, data cleaning includes handling missing values and outliers. Visualizations such as histograms, scatter plots, and bar charts provide clear insights into trends and patterns. For example, we explore the relationship between customer numbers and sales, analyze sales behavior during store opening times, and check how competition distance affects sales.

## Logging and Next Steps

The analysis is thoroughly logged using Python's `logging` library for traceability. Moving forward, insights from the EDA will inform the modeling phase, where we will build machine learning models to predict future sales based on the identified factors.
