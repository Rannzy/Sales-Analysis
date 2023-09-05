# Sales Analysis

# Data
The dataset contains imaginary data about sales of a tech retail store. It has 6 columns and 186850 rows.

# Data Cleaning
The dataset is observed to have no null values. However, it does have 618 duplicated values which are dropped from the dataset. 

# Sales analysis by month
The split function is applied to the order date column to obtain the month column. A new column 'sales' is also created which is a product of the 'quantity ordered' and 'price each' columns. A group function is then applied to obtain the sum of sales for each month. Through a bar chart visualization, it is observed that month 12 had the highest sales whereas month 1 had the lowest sales.

# Sales analysis by city
San Francisco city recorded the highest sales while Austin city recorded the least sales.

# Product Analysis
There are two observations from this segment. A sales analysis by sum showed that the Macbook Pro Laptop brought in the most amount for the company. This can be attributed to the fact that it is the most priced commdity  in the store. The AAA batteries (4-pack) brought in the least amount.
A count analysis revealed that the AAA batteries(4-pack) were the most bought commodity. The least bought item is the LG dryer. 

# Grouped Products
An analysis of products revealed that the iphone and lightning charging cable are frequently bought together.
