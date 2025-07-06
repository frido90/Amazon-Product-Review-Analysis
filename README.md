# Amazon Product Review Analysis
A detailed excel-based analytics project on Amazon product reviews, discounts, pricing, etc. This project is designed using calculated fields, pivot tables, interactive dashboard, and slicer to extract actionable insight on category trends, customer engagement, product performance and revenue opportunities.

### Project Overview
You are working as a Junior Data Analyst at RetailTech Insights, a company that provides e-commerce analytics solutions to sellers on platforms like Amazon. Your team has been tasked with analysing product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement. 

### Dataset Description
The dataset contains information scraped from Amazon product pages, including: 
- Product details: name, category, price, discount, and ratings
- Customer engagement: user reviews, titles, and content
- Each row represents a unique product, with aggregated reviewer data stored as comma-separated values
  
**Total Records: 1,463**
  
**Total Fields: 16 columns**

### Analysis Tasks     
Use pivot tables and calculated columns where necessary to answer the following: 
1. What is the average discount percentage by product category? 
2. How many products are listed under each category? 
3. What is the total number of reviews per category?  
4. Which products have the highest average ratings? 
5. What is the average actual price vs the discounted price by category? 
6. Which products have the highest number of reviews? 
7. How many products have a discount of 50% or more? 
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)? 
9. What is the total potential revenue (actual_price × rating_count) by category? 
10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)? 
11. How does the rating relate to the level of discount? 
12. How many products have fewer than 1,000 reviews? 
13. Which categories have products with the highest discounts? 
14. Identify the top 5 products in terms of rating and number of reviews combined. 

### Data Source
The primary data source used is Amazon case study excel file, an open source data that can be freely downloaded from an open source online site like Kaggle.

### Tool used & Environment
- Microsoft Excel
  - Named ranges and table referencing
  - Conditional formating
  - Pivot tables
  - Data Visualization
  - Slicer/Filter

### Key Analysis & Tasks
1. What is the average discount percentage by product category?
   - Inserted pivot table using average formula
2. How many products are listed under each category?
   - Inserted pivot table using count function
3. What is the total number of reviews per category?
   - Inserted pivot table using sum of rating count by category
4. Which products have the highest average ratings?
   - Inserted pivot table and sorted it based on average rating
5. What is the average actual price vs the discounted price by category?
   - Inserted pivot table and calculated based on average actual price and discounted price
  
### Analysed file
[Cleaned_Amazon case study.xlsx](https://github.com/user-attachments/files/21088926/Cleaned_Amazon.case.study.xlsx)

### Vusuals and Dashboards
![AMAZON Project](https://github.com/user-attachments/assets/2029fa22-0b0c-42f6-8b67-4598c2e8e376)

![Amaz1](https://github.com/user-attachments/assets/465c4dcb-2abf-40c3-b819-dec8cf217f9c)

![Amaz2](https://github.com/user-attachments/assets/6da67f9d-f247-4d15-96cf-b30a81a2b081)

### Skills and Competencies
- Data Cleaning: removed nulls, corrected inconsistent formats, changed the data type
- Data Aggregation: Used pivot tables and grouping to summarize key insights
- Excel formulas: Used formulas like IF, TRIM, PROPER, Calculated colums
- Visualization: Designed intuitive charts (bar, pie, line, card)
- Slicer/Filter: Enabled a dynamic filter for display
- Business insight: Was able to draw conclusion based on trends and business logics

### Business insights
- Electronics overwhelmingly dominate, generating ~₹98 billion in potential revenue
- Computers & Accessories and Home & Kitchen follow, with over ₹10 billion each.
- Niche categories like Health & Personal Care and Toys & Games contribute significantly less.
- High-priced items generate most of the revenue while Lower-priced items (<₹200) have the highest average rating, but limited revenue impact.
- Products with higher discounts tend to have marginally lower ratings, possibly due to quality perception or lower-tier inventory.




