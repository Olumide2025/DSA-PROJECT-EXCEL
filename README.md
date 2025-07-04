# DSA-PROJECT-EXCEL
## E-Commerce Analysis; Amazon As Case Study

### Project Overview
A detailed Excel-based analytics project on Amazon product reviews, discounts, and pricing. A project embarked on during my learning journey at DSA Incubator, this project makes pivot tables, slicers, calculated fields, and interactive dashboards to extract insights which can be put imto action on product performance, category trends, customer engagement, and revenue opportunities.

-  🔍 Objective: Analyze Amazon product and review data to derive business insights using pivot tables, slicers, calculated columns, and data visualizations.

## 🏢 Project Context
- ClientName: RetailTech Insights
- Industry: E-commerce Analytics
- Role: Junior Data Analyst
- Tools Used: Microsoft Excel (Pivot Tables, Charts, Conditional Formatting, Slicers, Cards)

## 🧾 Dataset Description
- Total Records: 1,465
- Columns: 16
- Source: Web-scraped Amazon product review data
- Each row represents: A unique product
- Column names included:
   - Product name
   - Category
   - Actual price & Discounted price
   - Discount %
   - Rating
   - Number of Ratings (Rating Count)
   - Review content (aggregated in some columns)
   - Revenue potential fields (derived)
# 📊 Key Analytical Tasks & Solutions
### | Task Description | Excel Tools Used |
1. What is the average discount % by product category?
  - Here I used the Pivot Table and Average Formula.
2. How many products are listed under each category?
  - The Pivot Table and Count was used here.
3. What is the total number of reviews per category?
  - The SUM function for Rating Count by category
4.	Which products have the highest average ratings?
  - This was sorted by calculating the Average Rating
5.	What is the actual vs discounted price by category?
  - Here I used the Grouped Bar Chart with the Pivot Summary
6.	Which products have the highest number of reviews?
  - Here the Sorting and Pivot Table was deployed.
7.	How many products have ≥ 50% discount?
  - The use Filter logic on Discount column was used to answer this question.
8.	What is the distribution of product ratings (e.g., 3.0, 4.0, etc.)?
  - Answered by grouping with histogram and Pivot Count.
9.	Total potential revenue (actual_price × rating_count) per category?
  - This is a derived (Calculated) Column + Pivot Table SUM
10.	Unique product count per price range bucket (<₹200, ₹200–₹500, >₹500)?
  - Using the IF function with the Donut Chart
11.	Relationship between rating and discount level?
  - This is done by Scatter Line Chart (2 y-axes)
12.	How many products have fewer than 1,000 reviews?
  - Deployed the COUNTIF Formula and Bar Chart
13.	Categories with highest average discount?
  - A sorted Pivot Table by Discount% was deployed
14.	Top 5 products by combined review count and rating	Ranking logic
  - using SUM(Rating × ReviewCount)

