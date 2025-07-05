# My-project-Documentation
My journey in building and analysing critical questions on a dataset

# Amazon Product Review Analysis Dashboard

## Overview
This project presents an analytical case study on Amazon product and customer review data, designed to provide insights for product improvement, marketing, and customer engagement. The work was carried out as a Junior Data Analyst at RetailTech Insights, a company specializing in e-commerce analytics for online marketplaces like Amazon.

### Dataset Description
- Source: Scraped Amazon product pages

- Records: 1,465 unique products

- Columns: 16 features including:

          - Product name, Category, Actual price, Discounted price, Rating, Rating count

          - Aggregated customer review content and metadata

  ### Project Goals
  Analyze product-level data to uncover actionable insights in areas like:

- Discount effectiveness

- Customer engagement & review volume

- Category-level pricing patterns

- Product rating distribution

- Revenue estimation

### Key Analysis Tasks

Each task was answered using Pivot Tables, Calculated Columns, and Excel Charts:

#	Question
1	What is the average discount percentage by product category?

2	How many products are listed under each category?

3	What is the total number of reviews per category?

4	Which products have the highest average ratings?

5	What is the average actual price vs the discounted price by category?

6	Which products have the highest number of reviews?

7	How many products have a discount of 50% or more?

8	What is the distribution of product ratings?

9	What is the total potential revenue (actual_price × rating_count) by category?

10	What is the number of unique products per price range bucket?

11	How does the rating relate to the level of discount?

12	How many products have fewer than 1,000 reviews?

13	Which categories have products with the highest discounts?

14	Identify the top 5 products in terms of rating and number of reviews combined.

### Dashboard Features 
Built entirely in Microsoft Excel, the interactive dashboard includes:

- Bar & Column Charts: Discount %, Review Count, Revenue by Category

- Scatter Plot: Relationship between Rating and Discount %

- Pivot Tables: For slicing data by Category, Price Range, Rating

- Slicers & Filters: To drill down by Category

- KPIs: Highlighting top-rated and most-reviewed products

### Tools Used

- Microsoft Excel (PivotTables, Charts, Slicers)

- Data Cleaning & Transformation

- Basic Calculated Fields (potential_revenue, price_range)

- Visual Dashboard Design

### Key Insights
- Electronics and Accessories offered the steepest average discounts.

- Products with higher discounts did not always correlate with higher ratings.

- A small number of products dominated in review volume and potential revenue.

- Over 200 products had discounts of 50% or more, representing major sales drivers.

- The majority of products fell into the ₹200–₹500 price bucket.

### Dashboards Included








![image](https://github.com/user-attachments/assets/b22539b8-cd2c-47ef-97b4-4f9130707719)










![image](https://github.com/user-attachments/assets/b816e373-aa4c-4a4f-badf-0e23f0c2f07b)








![image](https://github.com/user-attachments/assets/baf7555c-f0f9-4acb-958c-ccdfca3a5f3c)


###  Conclusion
This project demonstrates how Excel can be used not just for reporting but for end-to-end exploratory data analysis and dashboard creation. It bridges data cleaning, aggregation, visualization, and insight generation







# Palmoria Group HR Analytics Project

## Project Overview
his Power BI HR Analytics Dashboard analyzes gender inequality, pay gaps, and salary compliance at Palmoria Group, a manufacturing company in Nigeria. The project was developed to address media reports of gender bias and ensure fair compensation practices.

##  Business Problem

- Palmoria Group faced negative publicity due to gender inequality allegations, including:

- Gender pay gaps (Male employees earning significantly more)

- Unequal representation in leadership & technical roles

- Non-compliance with Nigeria’s $90,000 minimum salary regulation

### Data Sources & Cleaning

1. Employee Data (CSV)
Columns: Name, Gender, Department, Salary, Location, Rating

Cleaning Steps:

    - Replaced missing genders with "Undisclosed"

    - Removed employees with NULL departments

    - Filtered out employees without salary data

2. Bonus Rules (Excel)
 Structured as: Department → Performance Rating → Bonus %

- Transformed into a lookup table for DAX calculations

### Key Insights

Gender Distribution
 - 58% Male, 40% Female, 2% Undisclosed
 
 - Engineering & Product Management had the highest male dominance (70%)
 
 - Abuja had the most balanced gender ratio

2. Gender Pay Gap
 - Male employees earned $12K more on average
 - Engineering had the widest gap ($18K difference)
 - Kaduna region had the highest disparity ($14K gap)

3. Salary Compliance
 - 72% of employees earned below $90K (legal requirement)
 - Kaduna was worst (78% non-compliance)


4. Bonus Allocation
 - Total Bonus Payout = $X Million
 - Sales & Engineering received the highest bonuses
 - "Very Good" ratings got 6-8% bonuses


### Power BI Implementation

Features:
- Interactive filters (Gender, Department, Location)

 - Drill-down capability (Region → Department → Employees)

 - Dynamic measures (DAX for pay gap, compliance, bonuses)

Dashboard Pages:

Gender Overview

Pay Gap & Compliance

Bonus Calculations

Recommendations


###  Recommendations

Close the Pay Gap

- Audit salaries in Engineering & Product Management

- Adjust female salaries in Kaduna region

- Improve Gender Diversity

- Hiring quotas for women in male-dominated departments

- Leadership mentorship programs

- Meet Salary Regulations

- Prioritize raises for lowest-paid employees

- Phase in compliance within 12 months













