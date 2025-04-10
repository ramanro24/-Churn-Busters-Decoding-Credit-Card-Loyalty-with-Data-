# -Churn-Busters-Decoding-Credit-Card-Loyalty-with-Data-
# From Data to Dollars: Cracking Credit Card Attrition
# Overview
Why do credit card customers leave, and how can banks keep them? This project analyzes a dataset of 10,127 customers to uncover the drivers of churn, identify valuable segments, and boost revenue. Using machine learning and statistical techniques, I turned raw data into actionable insights for the financial sector.

# Business Questions
1. Why are customers leaving, and what’s pushing them out?
2. Who are the most valuable customers, and how do I retain them?
3. How does card usage (credit limit, utilization, transactions) affect churn and revenue?
4. How can customer info and habits optimize retention?
5. Who should I target for cross-selling or premium offerings?
# Dataset
Size: 10,127 customers
Features: Age, income, credit limit, transaction amounts/counts, relationship count, inactivity, and more
Target: Attrition_Flag (1 = Existing, 0 = Attrited)
Source: Anonymized credit card data (not included in repo for privacy)
# Methods
# Exploratory Data Analysis (EDA): 
Visualized patterns with bar graphs, boxplots, and correlation matrices.
# Logistic Regression: 
Explained 41% of churn, pinpointing inactivity and contacts as top churn drivers.
# Random Forest: 
Achieved 94.67% accuracy, highlighting transaction activity as key to retention.
# K-Means Clustering: 
Segmented customers into 3 groups (High Spenders, Moderate Spenders, Low Spenders).
# Statistical Tests: 
Chi-Square, ANOVA, Tukey HSD to validate income and relationship impacts.
# Key Findings
Churn Drivers: Inactivity and frequent contacts push customers away; more products and transactions keep them.
Valuable Segments: High earners (>$120K) contribute 35% of revenue; high spenders are profit stars.
Usage Impact: Low utilization with high limits signals retention; high utilization with low limits risks churn.
Revenue Boost: Target high spenders for premium offers, cross-sell to moderate spenders, and engage low spenders with high credit.
