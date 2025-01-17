# Bikes-Sales-Company-Project

----------------
## Overview
This project aims to offer insights into the characteristics that describe the target consumers, such as age, gender, occupation, region, and income. Additionally, the dashboard likely seeks to analyze customer preferences regarding bike purchases, including the number of bikes bought, car ownership, and the presence of children in the household.

## Dataset
The dataset consisted of many tables: Gender,Income,Children,Education,Occupation,Cars,Region,Age,Purchased Bike tables.

## Data Cleaning and Manipulation
Duplicate values were removed from all tables using their IDs. Age has been classified to three categories.

## Data Analysis and Result

![Bike Sales](https://github.com/user-attachments/assets/88e3f391-52e9-4334-8e0b-348ee831923c)

1.	Middle-aged customers constitute the largest demographic for bike purchases, accounting for 66% of sales, significantly outpacing adolescents (8%) and older adults (26%). 
2.	Car owners are twice as likely to purchase bikes compared to those who do not own cars.
3.	people with Professional Occupations represent the most significant group of bike buyers, comprising 30% of all sales, surpassing other occupational categories.
4.	Individuals with children are twice as likely to purchase bikes than those without children.
5.	North Americans are the dominant market for bike sales, with a 44% share, followed by Europe (31%) and the Pacific region (24%).

## Recommendation
--========== Explore the data ===========--

SELECT * FROM Pizzas;
SELECT * FROM Pizza_types;
SELECT * FROM Orders;
SELECT * FROM Order_details;

--========== Total Orders ===========--

SELECT Count(DISTINCT(order_id)) AS Total_Orders FROM Orders;
