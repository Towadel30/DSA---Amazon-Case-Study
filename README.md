# DSA---Amazon-Case-Study
### This is where i started my Portfolio building while taking my Data Analysis Class with the Incubator Hub during Digital Skill up Africa
# Project Topic: Amazon Product Review Analysis
Project Overview :You are working as a Junior Data Analyst at RetailTech Insights, a company that provides e-commerce analytics solutions to sellers on platforms like Amazon. Your team has been tasked with analysing product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.
Opened the original dataset on Microsoft Excel

Turned my dataset to table to enable me work on it using Ctrl+T

Started cleaning by first using delimeter to get my main category and delete the splitted columns and irrelevant columns too

Removed duplicates by navigating our "arrow" to the "data tab" — Remove duplicates. Made sure to repeat the process until there was no more duplicates. 

Created a new column for revenue on our worksheet as stated on our question, Multiplied "actual price" by "rating count" to arrive at our revenue

Created a new column products having a discount of 50% or more,=IF(Discount % >= 50, "Yes", "No

Add calculated column: Price Bucket Excel formular=IF(Discounted Price < 200, "₹200", IF(Discounted Price <= 500, "₹200–₹500", "₹500")

Add calculated column:excel formular==IF(Discounted Percentage<=10%,"0-10%",IF(Discounted Percentage<=20%,"11-20%",IF(Discounted Percentage<=30%,"21-30%",IF(Discounted 
Percentage<=40%,"31-40%",IF(Discounted Percentage<=50%,"41-50%",IF(Discounted Percentage<=60%,"51-60%",IF(Discounted Percentage<=70%,"61-70%",IF(Discounted Percentage<=80%,"71-80%",IF(Discounted Percentage<=90%,"81-90%","91-100%")))))))))

Created our pivot table by navigating our "arrow" to the to the "insert tab" — pivot table. Made sure our pivot is on a new worksheet and not an existing worksheet to ensure we have a clean pivot table

Started answering the questions on our case study by creating the pivot tables as requested

Created another sheet for Dashboard
