# SQL e-commerce query

![ecommerce_photo](https://user-images.githubusercontent.com/63714618/121355974-b8255680-c930-11eb-81f2-9cee11e1920d.jpg)


We have a data base from an e-commerce which sells products for health and wellness. The data base was originally a csv file which was converted to db in a previous notebook. Since we are focusing on SQL queries, we don't show the previous code for EDA (Exploratory Data Analysis) and db conversion.

This is a descriptive screenshot for the different columns:
- created_at : timestamp of when order is created
- order_number : self-explanatory
- sku: unique reference for each product
- total_order_price: self explanatory
- code: the discount code applied to this order

![database](https://user-images.githubusercontent.com/63714618/121350860-70500080-c92b-11eb-8537-f85f8afe5723.png)

We use SQL query to answer the following questions:

- How many orders per day? 
- How much sales per day?
- What is the top selling product?
- What percentage of orders are with discount codes?
- What percentage of orders include the product with SKU PM591?
- Which hour of day do people buy most products?
