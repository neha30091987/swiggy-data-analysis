# swiggy-data-analysis

This repository contains an indepth analysis of swiggy database using SQL. The investigation was carried out to address various business inquiries, utilizing SQL queries to extract valuable insights from the dataset.


**TOOLS USED**:  MySQL WorkBench 8.0

**About Dataset** 
The analysis makes use of several tables from the swiggy database, encompassing
Tables: user(user_id,name,email,password),
restaurants(r_id,r_name,cuisine),
food(f_id,f_name,type),
menu(menu_id,r_id,f_id,price),
orders(order_id,user_id,r_id,amount,date,partner_id,delivery_time,delivery_rating,restaurant_rating),
delivery_partner(partner_id,partner_name),
order_details(id,order_id,f_id).


**The project addresses the following questions:**
Swiggy Case Study-

1. Find customers who have never ordered.
2. Average Price/dish.
3. Find the top restaurant in terms of the number of orders for a given month.
4. Restaurants with monthly sales greater than x.
5. Show all orders with order details for a particular customer in a particular date range.
6. Find restaurants with max repeated customers. 
7. Month over month revenue growth of swiggy.
8. Customer - favorite food.

**Query and Result**
Each query is tailored to address a specific question by joining multiple tables, applying aggregations, filters, and sorting to derive the necessary information from the data.

**Author**
Neha Sharma
Github-nehasharma30091987
Linkedin-https://www.linkedin.com/in/neha-sharma-dataanalyst
