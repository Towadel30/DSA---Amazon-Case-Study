# DSA---Amazon-Case-Study
### This is where I started my portfolio building while taking my data analysis Class with the Incubator Hub during Digital Skill up Africa
### Project Topic: Amazon Product Review Analysis
Project Overview :This Data Analysis aims to analyze product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.
### Data Source 
DSA Data Analysis Capstone Project 
### Tools Used
Ms Excel for Data Cleaning and Exploratory Data Analysis (EDA) 
- Opened the original dataset on Microsoft Excel [Download here](https://www.microsoft.com/en-gb/microsoft-365/excel)

### Data Cleaning and Preparation
- Data loading and Inspection
- Handling missing variables
- Data Cleaning and formating

### Exploratory Data Analysis
The dataset contains information scraped from Amazon product pages, including: 
•       Product details: name, category, price, discount, and ratings 
•       Customer engagement: user reviews, titles, and content 
•       Each row represents a unique product, with aggregated reviewer data 
stored as comma-separated values 
Total 
Records: 
1,465 
TotalFields: 16 columns

### Data Analysis
- Turned my dataset to table to enable me work on it using Ctrl+T

- Started cleaning by first using delimeter to get my main category and delete the splitted columns and irrelevant columns too

- Removed duplicates by navigating our "arrow" to the "data tab" — Remove duplicates. Made sure to repeat the process until there was no more duplicates. 

- Created a new column for revenue on our worksheet as stated on our question, Multiplied "actual price" by "rating count" to arrive at our revenue

- Created a new column products having a discount of 50% or more,=IF(Discount % >= 50, "Yes", "No

- Add calculated column: Price Bucket Excel formular=IF(Discounted Price < 200, "₹200", IF(Discounted Price <= 500, "₹200–₹500", "₹500")

- Add calculated column:excel formular==IF(Discounted Percentage<=10%,"0-10%",IF(Discounted Percentage<=20%,"11-20%",IF(Discounted Percentage<=30%,"21-30%",IF(Discounted 
Percentage<=40%,"31-40%",IF(Discounted Percentage<=50%,"41-50%",IF(Discounted Percentage<=60%,"51-60%",IF(Discounted Percentage<=70%,"61-70%",IF(Discounted Percentage<=80%,"71-80%",IF(Discounted Percentage<=90%,"81-90%","91-100%")))))))))

- Created our pivot table by navigating our "arrow" to the to the "insert tab" — pivot table. Made sure our pivot is on a new worksheet and not an existing worksheet to ensure we have a clean pivot table

- Started answering the questions on our case study by creating the pivot tables as requested

- Created another sheet for Dashboard

![image](https://github.com/user-attachments/assets/c8d1b0f7-6841-4c73-b410-d72ece6938bb)
### Result Findings
1. Category by Average of Discount Percentage
This chart shows the average discount percentage across different product categories.
Home Improvement has the highest average discount at 58%, followed by Computers & Accessories (54%), Health & Personal Care (53%), and Electronics (50%), Office Products (12%) and Toys & Games (0%) have the lowest or no discounts.
The discount level varies significantly, which may affect consumer purchase behavior — higher discounts often drive more attention.

2. Category by Product Name 
This chart shows the number of products listed under each category
Computers & Accessories and Home & Kitchen have the highest product counts (511 and 448 respectively).
Categories like Car & Motorbike and Toys & Games only have 1 product each.
This tells us which categories are most represented in the dataset — likely areas where Amazon has a broader inventory or focus.

3. Category by Average Actual Price and Discounted Price (Right Chart)
This line chart compares the average actual price vs. the discounted price per category.
Electronics stand out with a sharp peak — high average actual price and significant discount.
Other categories like Musical Instruments and Health & Personal Care also show notable price differences.
Toys & Games and Office Products show almost no difference — likely due to low or no discounts, as shown earlier.
The gap between actual and discounted prices reflects how much customers are saving — useful for pricing strategies.

4. Category by Sum of Rating Count
This chart shows the rating across different category and the higest is Electronics with 15,595,997

5. Category by Sum of Revenue
This chart shows the revenue across different category and the higest is Electronics with 96,936,506,025

6. Discount Bucket by Average Rating
This chart shows the average rating of the discount bucket and the higest 4.2 are within 0-10%, 21-30% and 91-100%

7. Price Bucket by Sum of Product Name
This chart shows the price bucket by sum of product name, ₹200	is 169, ₹200–₹500	is 351 while
₹500	is 869 
  
8. Category by Maximum of Discount Percentage
This chart shows the maximum discount percentage across different category and the higest is Computer Accesssories with 94%
