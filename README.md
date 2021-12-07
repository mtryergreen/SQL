## Overview 
This was the most fun module thus far. The process went from conceptualizing the data tables and how they connected with diagrams in QuickDBD to importing the .csv data sets into dataframes that I constructed in pgAdmin. 

## Tools
- PostgreSQL 11.14 (has been debugged the most) without Stack Builder for tables and their predefined relationships
<img width="443" alt="Screen Shot 2021-11-29 at 7 49 34 PM" src="https://user-images.githubusercontent.com/89936913/143982575-252f5e9e-5296-4f2e-a402-95a00f32875a.png">
- pgAdmin to write and execute quer

## Deliverable 1: The number of retiring employees by title
I'll create a table for Retirement Titles that utilizes the the ERD (entity relationship diagram) I created earlier in this module. Because some employees have multiple titles due to promotions, I'll need to use the 'DISTINCT ON' statement and 'COUNT()' function. 

It's important to keep track of retiring employees because the 'Silver Wave' could catch a company off guard and with a reduced workforce if they do not move to hire and train new skilled employees in time. 
The number of retiring employees was collected in the following table, though there are many duplicates present: 

## Retirement Titles

![Retiring Titles](https://user-images.githubusercontent.com/89936913/144991735-1f4569e7-96eb-4012-a10f-10fde29bd16c.png)

To eliminate the duplicates and keep only unique names relating to most recent employee positions, I used the select distinct function to create another table with only the unique names: 

## Unique Titles

![Unique retirement titles](https://user-images.githubusercontent.com/89936913/144992406-fc2aefee-3f03-493c-a991-51ab33ebfa87.png)

I'll create another table for unique employees by most recent job who are also about to retire: 

## Retiring Titles

![Screen Shot 2021-12-07 at 12 41 22 AM](https://user-images.githubusercontent.com/89936913/144995765-fe57388b-75a7-4372-86d7-85b23873f1ed.png)



## Deliverable 2: The employees elligible for the mentorship program
I'll again use the ERD and queries to create a mentorship eligibility table by organizing primary keys, foreign keys and the data types. 

![Screen Shot 2021-12-07 at 1 08 55 AM](https://user-images.githubusercontent.com/89936913/144999880-3984e132-8b69-479f-b73a-91e7eb207d1d.png)


## Deliverable 3: Written report on employee database analysis


