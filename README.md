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

### Visual and Insights
![Screenshot_20250704-204901](https://github.com/user-attachments/assets/547321f5-5ed7-4741-a3d7-60f83def1cd2)
![Screenshot_20250704-204941](https://github.com/user-attachments/assets/b349daa2-ac97-4d47-b5d7-e761b067b131)
![Screenshot_20250704-205017](https://github.com/user-attachments/assets/ad84dffa-6877-4b68-aa32-d9cfbcc20e71)
![Screenshot_20250704-205209](https://github.com/user-attachments/assets/f2a90770-b07a-4731-a192-f4017b6e1fb0)











### 🧠 Key Highlights from Dashboard:
- Discount vs Rating: Discounted products have low rating.
- Price Range Bucket: Large percentage of products fall under the affordable to mid expensive range.
- Revenue Potential: Dominance of categories like Home Kitchen and Electronics dominate in potential revenue.
- Category-wise Review Count: Electronics and accessories are more reviewed bu the users.
- Top 5 Products: Based on high review count and strong ratings.
- Discount Percentage by Category: Health and home products are the most discounted products.

### 🧠 Skills & Competencies Demonstrated
Skills and How it was applied
- Data Cleaning: I removed nulls, corrected inconsistent formats, trimmed text
- Data Aggregation: I used pivot tables and grouping in summarizing the key insights
- Excel Formulas	IF, COUNTIF, AVERAGEIFS, PROPER, TRIM and calculated columns
- Visualization Designed intuitive charts (bar, pie, line, donut, cards)
- Slicers & Cards	was enabled tp help in the dynamic filtering and KPI display of insights
- Business Analysis: Conclusions were drawn based on data trends and business logic

### 💡 Summary of Business Insight
- High Discount is not equal to High Rating: Many discounted items witnessed poor ratings. cutting down prices alone won’t ensure customer satisfaction, they need more assurance.
- Most Reviewed Category: Electronics stands as the most reviewed product category which shows high satisfaction.
- Revenue Optimization: More focus should be on marketing mid-priced, highly rated products in "Home Kitchen" and "Accessories".
- Product Opportunity: Products with moderate ratings but high volume reviews may benefit from improved quality or targeted feedback campaigns.
- Outlier Products: A few products drive massive engagement. Promoting these further can help with cross-selling.

### 🔧 Tools & Environment
- Microsoft Excel
- Pivot Tables
- Data Visualizations (Bar, Line, Donut, Cards)
- Slicers & Filters
- Conditional Formatting
- Named Ranges & Table References

### About Me
Yusuf Olumide Damilare
B.A English and Literary Studie | Data Analyst
Passionate about data becoming visuals which will impact and help businesses grow for decision making. This is a project that has helped my learning journey to profiecinecy in Excel-based analysis.

### Contact
- Email: appositive20@gmail.com
- Phone: +234 701 206 2055
