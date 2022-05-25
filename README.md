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
* I checked for duplicate records but discovered there was none because each row in the dataset represents the record for each customer's demographics, product preferences, channels performance and campaign success history.
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

![alt text]https://github.com/RukkyE/Maven-Marketing-Campaign-Analysis/blob/main/Images/Website%20Purchases%20By%20Education%20and%20Enrollment%20Year.PNG

* __Website Purchases By Country and Age Grade__: 'Spain' has the highest records of 4,382 website purchases of which 2,350 of the customers are 'Middle-Aged' while 'Mexico' has the least records of 18 website purchase of which 2 of the customers are 'Middle-Aged'.
* __The Channels that are Underperforming__: 'Deals Purchases' is the least performing channel with 12,970 purchases which is 39% while 'Catalog Purchases' is the second least performing with 9,150 purchases which is 27%.
* __The Most Successful Campaign__: 'Last Campaign' is the most successful campaign with 334 customers who accepted while 'Campaign 2' is the least successful with 30 customers.
* __The Best Performing Products__: 'Wine' is the best performing product with $680,816 spent by customers while 'Meat' is the second best performing product with $373,968 spent.
* __Average Income By Country and Age Grade__: Based on Customers' Demographics, the highest category of customers are 'Adults in Mexico' with an average income of $70,515 while the least category are 'Adults in Australia' with an average income of $42,610.

## Recommendations
From my analysis, the following recommendations will help to increase customer numbers and product purchases;
* For Website Purcahses by Education, marketing should be focused on 'Graduates', 'PhD' and 'Master' degree holders who have the resources such as knowledge and finance in terms of purchasing data to access the company's website to purchase products.
* For Website Purchases by Country and Age Grade, marketing should be focused on the middle-aged in countries like Spain, Saudi Arabia and Canada
* For channels or media through which customers make purchases, the Marketing team can introduce other media such as Social Media channels like Instagram, Facebook etc.
* For the best performing products like Wine, Meat, Gold and Fish, marketing should be more focused on these products as fruits are perishable and cannot be preserved for long while sweets are not frequently bought by Adults, Middle-Aged or Seniors.
* The Marketing team should focus on organizing campaigns and running advertisement in countries with the higest average income like Mexico targeting Adults and Saudi Arabia targeting Seniors.

## Relevant Link
* [LinkedIn](https://www.linkedin.com/in/rukevweevwrujae/)
