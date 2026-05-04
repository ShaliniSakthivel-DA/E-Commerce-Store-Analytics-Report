# E-Commerce-Store-Analytics-Report
This project analyzes an e-commerce dataset using PivotTables to identify sales trends across categories, regions, customers, discounts, and payment methods. It highlights strong contributions from Sports, Online sales, Platinum customers, and female shoppers, with steady year-on-year growth, helping understand revenue drivers and customer behavior.

# Objectives

* Analyze sales performance across categories, regions, stores, and time to find growth areas.
  
* Understand customer behavior based on loyalty, gender, and spending patterns.
  
* Study how discounts affect sales and identify effective pricing strategies.
  
* Identify top brands and customers contributing most to revenue.
  
* Track monthly and yearly sales trends to measure business growth.
  
* Provide insights to improve sales, customer loyalty, and overall profit.

# Dataset Description

Sales Details: Includes Sales_ID, order date, year, quantity, price, discount, total price, and payment method.

Customer Details: Contains Customer_ID, name, gender, age, and loyalty level.

Product Details: Includes Product_ID, category, brand, and cost.

Store Details: Contains Store_ID, city, region, and store type (Online, Flagship, etc.)

# Data Cleaning Process (Excel & Power Query)

**In Excel**

* Removed duplicate records.
  
* Filled missing values using basic formulas (price, discount, total).
  
* Standardized formats (dates, gender, loyalty, discount %).
  
* Used Find & Replace to fix ID errors (Customer_ID, Product_ID).
  
* Applied conditional formatting to find errors in price and cost.
  
* Converted all columns to correct data types (text, number, percentage).
  
**In Power Query**

* Removed duplicate records.
  
* Fixed spelling and data inconsistencies (IDs, categories, brands, locations).
  
* Merged Customer, Product, Store, and Sales tables into one dataset.
  
* Cleaned column names and removed extra spaces.
  
* Set correct data types (dates, numbers, percentages).
  
* Automated steps so data can be refreshed easily.

# Data Imputation

* Data imputation means filling missing values to keep the data complete and accurate.

* Missing Discount % was calculated using Unit Price, Quantity, and Total Price.
  
* Missing Unit Price was calculated using Total Price, Quantity, and Discount %.
  
* Missing Total Price was calculated using Quantity, Unit Price, and Discount %.

This helped make the dataset complete and ready for analysis and dashboards.

# Data Exploration

**Total Price**

* Average transaction value is ~1087, while the median is lower (~869), showing more small purchases and a few large ones.
  
* Values vary widely, indicating different spending levels.
  
* Data is slightly skewed, meaning a few high-value transactions increase the average.
  
**Unit Price**

* Average price is ~514, close to the median (~523), showing balanced pricing.
  
* Prices range from very low to high, indicating variety in products.
  
* Distribution is almost even, with most products priced around 500.

# Pivot Table Insights:

**1. Sales by Category** 

* Sports has the highest sales (~$5.4L).

* Electronics and Home also contribute well.

* Total sales are ~$21.7L.

**2. Sales by Region & Store Type**

* East, North, and South regions perform strongly.
  
* Online sales are highest, followed by Flagship stores.
  
**3. Customer & Gender Analysis**

*  Platinum customers contribute the most.
  
*  Female customers make more purchases than males.
  
**4. Discount Impact**

*  Medium discounts (13–16%) drive higher sales.
  
*  Very high discounts do not always increase sales.
  
**5. Yearly Sales Trend**

* Sales show steady growth.
  
* 2024 recorded the highest sales.
  
**6. Top Brands**

*Few top brands contribute a large share of revenue.

**7. Average Purchase Value**

* Female customers spend slightly more than males.
  
**8. Payment Method & Discounts**

* Discounts are evenly distributed across payment methods.
  
**9. Top Customers**

* Top 10 customers contribute a significant portion of sales.
  
**10. Monthly Sales Trend**

* Sales are stable across months, with small variations.

**11. Sales by Store Type**

* Online has the highest transactions, followed by Flagship and Outlet.

<img width="1707" height="493" alt="image" src="https://github.com/user-attachments/assets/c4aa8643-c8a8-4cc6-bb13-1e4fe61bd1a7" />

# Project Insights

# 1. Descriptive Analysis

* Sports category has the highest sales.
* Online stores perform the best.
* Platinum customers spend the most.
* Female customers buy more and spend slightly higher.
* Medium discounts (13–16%) work better.
* Sales increased, with 2024 being the best year.
* Few top brands and customers bring most revenue.
* March is the highest sales month, May is the lowest.
* Payment methods are almost equal.
  
# 2. Diagnostic Analysis 

* Sports products are more popular.
* Online shopping is easy and convenient.
* Loyalty programs encourage higher spending.
* Female customers show higher buying interest.
* Medium discounts attract more customers.
* Growth is due to more customers and better sales strategy.
* Sales depend on top brands and key customers.
* Seasonal demand affects monthly sales.
* Customers use all payment options equally.
  
# 3. Predictive Insights 

* Sports category will continue to grow.
* Online sales will increase more.
* Loyalty customers will keep spending more.
* Female customers will remain important.
* Medium discounts will stay effective.
* Sales will keep growing but slowly.
* Businesses may focus on keeping top customers.
* Seasonal trends will continue.
* Digital payments may increase more.

# Conclusion

Sales are mainly driven by Sports products, Platinum customers, and online sales. Medium discounts work best. Female customers buy more and spend slightly higher than males. Sales grew steadily, with 2024 as the best year. Overall, the project shows how data tools help understand sales and make better decisions.
#Excel #DataAnalysis 
