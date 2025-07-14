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
- Visualization and Dashboard Design

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

<img width="2013" height="2755" alt="image" src="https://github.com/user-attachments/assets/3052d955-57c1-4f61-b012-6a1afce153bb" />


### Result Findings
 **Dashboard Interpretation**

###  1. **Category by Average of Discount Percentage**

> **What it shows:** The average discount % for each product category.

| Category                | Avg. Discount |
| ----------------------- | ------------- |
| Home Improvement        | 58%           |
| Computers & Accessories | 54%           |
| Health & Personal Care  | 53%           |
| Musical Instruments     | 46%           |
| Car & Motorbike         | 42%           |
| Home & Kitchen          | 40%           |
| Office Products         | 12%           |
| Toys & Games            | 0%            |

 **Interpretation:**

* **Home Improvement** and **Computers & Accessories** give the highest average discounts, which may be used to boost sales or offload inventory.
* **Office Products** and **Toys & Games** have very low or no discounts, possibly due to low competition or limited data.

###  2. **Category by Product Name (Count of Products)**

> **What it shows:** How many products are listed under each category.

 **Interpretation:**

* **Electronics, Home & Kitchen, and Computers & Accessories** have the **highest number of products**, indicating they’re popular selling categories.
* Very few products exist in **Car & Motorbike**, **Toys & Games**, and **Home Improvement**, showing limited variety or focus.

###  3. **Category by Sum of Rating Count**

> **What it shows:** The total number of reviews per category (sum of user ratings).

 **Interpretation:**

* **Electronics** alone has over **15 million ratings**, indicating extremely high customer engagement and sales volume.
* **Home & Kitchen** and **Computers & Accessories** also have millions of ratings.
* Low-review categories (e.g. **Car & Motorbike**, **Toys & Games**) might not be high-volume or have just a few popular items.

###  4. **Product Name by Rating**

> **Top 5 highest-rated products:**

* REDTECH USB-C Cable – ★5.0
* Amazon Basics Mouse – ★5.0
* Syncwire Cable – ★5.0
* Swiffer Water Heater Faucet – ★4.8
* Instant Pot Air Fryer – ★4.8

 **Interpretation:**

* These are the **best-rated products**, possibly because of excellent quality or performance.
* Great for case studies or marketing highlights.

###  5. **Category by Average Actual Price and Discounted Price**

> **Line chart comparing original and discounted prices per category.**

 **Interpretation:**

* **Electronics** and **Home & Kitchen** are the most expensive, even after discounts.
* **Toys & Games** and **Office Products** are the cheapest, with minimal price drops.

 **Business takeaway:** High-priced categories are being discounted, which may signal fierce competition or customer sensitivity to price.

###  6. **Reviewed Products**

> Top 5 products by **number of reviews**:

* AmazonBasics HDMI Cable – **426,973**
* boAt Bassheads Earphones – **363,713**

 **Interpretation:**

* These are **best-selling or most widely used** products.
* High review counts mean high consumer trust, reach, and feedback — great for promoting as flagship items.

###  7. **Category by Revenue**

> Shows **total revenue = actual price × review count**.

 **Interpretation:**

* **Electronics** brings in the **highest revenue (₦91B+)**, dominating the market.
* **Computers & Accessories** and **Home & Kitchen** follow.
* **Toys & Games** and **Car & Motorbike** generate the **least revenue**.

 **Business insight:** Electronics should be a focus area for promotions and restocking.


###  8. **Price Bucket by Product Name**

> Pie chart of price categories:

* Majority of products are **above ₹500**
* Some are in ₹200–₹500 range
* Few are under ₹200

 **Interpretation:**

* Amazon sells mostly **mid- to high-priced** products.
* Could suggest higher margins and better quality perception.

###  9. **Discount Bucket by Average Rating**

> Compares **discount levels vs average rating**.

 **Interpretation:**

* Products with **lower discounts (0–10%)** have **higher ratings (\~4.3)**
* Products with **50%+ discounts** show **lower ratings (below 4.0)**

 **Conclusion:** Deep discounts may harm perceived quality, or poor-performing products are being discounted heavily.


###  10. **Category by Maximum Discount Percentage**

> Shows the **highest single discount** in each category.

| Highest Discounts:            |
| ----------------------------- |
| Computers & Accessories – 94% |
| Electronics – 91%             |
| Home & Kitchen – 90%          |
| Office Products – 75%         |

 **Interpretation:** These deep cuts may be used for clearance or promotions.


###  11. **Product Name by Rating and Review Count**

> Bar chart showing both **rating** and **review count** for top products.

 **Interpretation:**

* AmazonBasics HDMI and boAt Bassheads have **both high ratings and high reviews**, making them excellent performers.
* Products with high ratings but **low reviews** may be newer or niche.


##  SUMMARY

> This dashboard presents a comprehensive analysis of Amazon product performance using metrics like **discounts, ratings, reviews, price ranges, and revenue**.

> * Electronics dominate in **volume, reviews, and revenue**
> * Top-rated products include REDTECH, Syncwire, and Amazon Basics accessories
> * Higher discounts often correlate with **lower ratings**
