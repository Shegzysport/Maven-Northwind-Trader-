# Maven-Northwind-Trader
 A top-level KPI dashboard to help Northwind Traders' executives quickly understand the company's performance
 # INTRODUCTION
 For this challenge, I worked as a BI developer for Northwind Traders, a global import and export company that specializes in supplying high-quality gourmet food products to restaurants, cafes, and specialty food retailers around the world.
 # OBJECTIVE
The main objective of this task is to Build a top-level KPI dashboard to help Northwind Traders' executives quickly understand the company's performance in key areas like;
* Sales trends
* Product performance
* Key customers
* Shipping costs
# DATA SOURCE
The data was obtained from the Maven Analytics website.
# DATA PREPARING & CLEANING
* The data was loaded into Power BI and it is a CSV file.
* The data has 7 different tables
* For the customer table; the first row was made as the headers
* For the order_details table; a new column was added for the price paid. This was calculated by using = ([unitprice] * [Quantity] * (1-[discount])
 * Because the data is already cleaned, the relationship between the data was already formed.
# VISUALIZATION 
The visualization was done using Power Bi

![DASH](https://github.com/Shegzysport/Maven-Northwind-Trader-/assets/152897788/d32dfec6-7ca9-4b3a-ad8b-f524ed7a1512)

# FINDINGS
* About sales: The highest sales of $123,798.00 was made in April 2 2015 and it falls rapidly in May 2 2015 to $18,333.00 was make it the lowest sales month.
* The highest category of product sold between 2013 to 2015 are Beverages which generated over $267,000 followed by dairy products which is over $234,000 followed by 
  confections which is over $167,000 followed by meat and poultry which is over $163,000 followed by seafood over $131,000 and condiments which is over $106,000 followed by 
  produce over $99,0000 and lastly $95,000 of grains and cereals.
  All this are generated from 91 customers in 21 countries where USA and Germany contributed most, Australia and brazil so on.
* And the shipping: Total shipping cost is $64,940.00 where 326 orders was shipped through United Package which cost 39.28% of shipping cost followed by Speedy Express which 
  is about 30.72% and the least is Federal Shipping which is 30%.

