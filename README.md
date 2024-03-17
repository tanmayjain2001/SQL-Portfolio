# SQL-Portfolio
Welcome to my SQL Portfolio repository! This repository contains a collection of SQL projects that demonstrate my skills and expertise in working with databases. Each project is accompanied by SQL code, documentation, and sometimes additional resources.

# Table of Contents -

# (1.) Cyclistic Case Study

Case study about a fctional company "Cyclistic".

About Cyclistic In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime.

GOAL Three questions will guide the future marketing program:

How do annual members and casual riders use Cyclistic bikes differently?
Why would casual riders buy Cyclistic annual memberships?
How can Cyclistic use digital media to influence casual riders to become members?
Approach -

I downloaded all 12 datasets of year 2023
Then I loaded them into SSMS, where cleaning and data transformation takes place.
First I created an empty table with a schema according to my requirements and then I inserted all the data from 12 tables according to the dataset I created earlier
Then I checked for NULL values and eleminated them.
Also I checked for duplicate values.
Then I checked for negative value in Duration column as duration cannot be negative.
After going through all these steps I had data ready for analysis!

Project is done in 3 steps - 
1. Combining the datasets
2. Cleaning the dataset.
3. Analizing the cleaned data.

# (2.) Nashville Housing Project

Project focused on cleaning the dataset found in the .xlsx file, which contains information about the housing market in Nashville.

After importing that file in SSMS and creating the table on which we will be working, we start by displaying and checking the raw data.

Now we are ready to continue with the following steps-procedures:

(i.) Standardize Date Format

(ii.)  Populate Property Address data

(iii.)  Breaking out Address into Individual Columns (Address, City, State)

(iv.) Change Y and N to Yes and No in "Sold as Vacant" field.

(v.) Remove Duplicates

(vi.) Delete Unused Columns

(vii.) Final Check: simply taking a final look of the updated and cleaned table.

Results
After all those manipulation and cleaning procedures, the original dataset, which initially consisted of 56477 rows, ends up in a table format, including 56373 rows. In conclusion, we can confidently claim that we cleaned the dataset efficiently enough and brought in a format suitable for future analysis, by only missing 104 rows or the 0.002% of the raw data.



# (3.) Danny's Diner 


## INTRODUCTION

Danny seriously loves Japanese food so in the beginning of 2021, he decides to embark upon a risky venture and opens up a cute little restaurant that sells his 3 favourite foods: sushi, curry and ramen. Danny’s Diner is in need of your assistance to help the restaurant stay afloat - the restaurant has captured some very basic data from their few months of operation but have no idea how to use their data to help them run the business.

## Problem Statement

Danny wants to use the data to answer a few simple questions about his customers, especially about their visiting patterns, how much money they’ve spent and also which menu items are their favourite. Having this deeper connection with his customers will help him deliver a better and more personalised experience for his loyal customers.

He plans on using these insights to help him decide whether he should expand the existing customer loyalty program - additionally he needs help to generate some basic datasets so his team can easily inspect the data without needing to use SQL.

Danny has provided you with a sample of his overall customer data due to privacy issues - but he hopes that these examples are enough for you to write fully functioning SQL queries to help him answer his questions!

Danny has shared with you 3 key datasets for this case study:

- sales
- menu
- members
-
-You can inspect the entity relationship diagram and example data below.

- ![Danny's Diner (1)](https://github.com/tanmayjain2001/SQL-Portfolio/assets/99605845/de7b2cca-4c8f-4308-babb-66830fafc763)

### **Table 1: sales**

The `sales` table captures all `customer_id` level purchases with an corresponding `order_date` and `product_id` information for when and what menu items were ordered.


### **Table 2: menu**
The menu table maps the product_id to the actual product_name and price of each menu item.


### **Table 3: members**
The final members table captures the join_date when a customer_id joined the beta version of the Danny’s Diner loyalty program.






