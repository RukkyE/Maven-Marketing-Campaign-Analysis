# Maven-Marketing-Campaign-Analysis
A repository for the analysis of the records of customers for the Maven Marketing Campaign using Microsoft Excel
The datasets used for this project are included in the repository. <br />

## Introduction
In this project, I analysed the records of 2,240 customers for the Maven Marketing Campaign based on the customers' profiles, product preferences, campaign successes or failures and channel performance. <br />
The aim of the project is to analyse;
* The factors significantly related to the number of web purchases. <br />
* The most successful marketing campaign. <br />
* What the average customer looks like. <br />
* The best performing products. <br />
* The channels that are underperforming. <br />

## Data Cleaning
The dataset of this project contains 1 CSV file with 2,240 records and 28 fields which I imported into Microsoft Excel Query Editor. The following are the cleaning steps I performed;
* I checked for duplicate records but discovered there was none because each row in the dataset represents the record for each customer's demographics, purchases and campaign acceptance history.
* I also checked for "blank" cells, which I found in the "income" column and replaced them with 0 using the 'Find and Replace' function.
* I converted the 'Year of Birth' column to 'Age' by subtracting from the current year '2022' and also created a new column for 'Age Grade' which 'Adults' are customers less than 40 years, 'Middle Age' are those from 41 - 59 years and 'Seniors' are those above 59 years.
* I also created a 'Year' column from the 'Customer Enrollment Date' column.

## Data Exploration
The following are some of the key insights I generated;
* Total Customers = 2,240
* Average Income of Customers = $51,687.46 
* Total Website Purchases = 9,150
* Total Complains = 21
* Total Website Visits Last Month = 11,909

## Insights From My Analysis
* __Website Purchases By Education and Enrollment Year__: 'Graduation' level customers who enrolled in 2013 have the highest records of 2,527 website purchases while 'Basic' level customers who enrolled in 2014 has the least records of 16 website purchases.
* __Website Purchases By Country and Age Grade__: 'Spain' has the highest records of 4,382 website purchases of which 2,350 of the customers are 'Middle-Aged' while 'Mexico' has the least records of 18 website purchase of which 2 of the customers are 'Middle-Aged'.
* __The Channels that are Underperforming__: 'Deals Purchases' is the least performing channel with 12,970 purchases which is 39% while 'Catalog Purchases' is the second least performing with 9,150 purchases which is 27%.
* __The Most Successful Campaign__: 'Last Campaign' is the most successful campaign with 334 customers who accepted while 'Campaign 2' is the least successful with 30 customers.
* __The Best Performing Products__: 'Wine' is the best performing product with $680,816 spent by customers while 'Meat' is the second best performing product with $373,968 spent.
* __Average Income By Marital Status and Age Grade__: Based on Customers' Demographics, the highest category of customers are 'Divorced Seniors' with an average income of $55,376 while the least category are 'YOLO Middle-Aged' with an average income of $48,432.

## Recommendations
From my analysis, the following recommendations will help to increase customer numbers and product purchases;
* From the trend during certain months in the year, there was a spike in revenue generated and quantity sold e.g February to March and April to May in 2018, also from February to March and April to May in 2019. During these time periods when there is increase in sales, marketing strategies to increase customers should intensify. Also during time period when there is a decline in sales, strategies to reduces prices of items such as 'Sales Promo' should be put in place. 
* The Marketing and Communications team should communicate effectively to companies who placed orders for items but did not purchase by sending them marketing materials such as emails, advertisements etc to enable them make a buying decision.
* For channels or media through which customers make purchases, the Marketing team can introduce other media such as Social Media channels like Instagram, Facebook etc.
* Incentives, bonuses and promotion should be given to the top 3 sales persons with the highest sales and revenue generated yearly. This will encourage those sales persons like 'Kim Fishman' and 'Ann Lee' to put in more effort in making more sales.
* The prices of items in California and New Mexico should be reduced to increase demand and sales of items.
* The price of Item 5 should be reduced to increase demand and thus the quantity sold while the prices of Items 3 and 4 should be increased since the demand and quantity sold is high.

## Relevant Link
* [LinkedIn](https://www.linkedin.com/in/rukevweevwrujae/)
