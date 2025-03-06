## Description:

This lab contains a SQL injection vulnerability in the product category filter. When the user selects a category, the application carries out a SQL query like the following:

SELECT * FROM products WHERE category = 'Gifts' AND released = 1

To solve the lab, perform a SQL injection attack that causes the application to display one or more unreleased products.


## Steps to Exploit:

1. Identify the part of request used to display the products.

2. Modify the category parameter, giving it the value '+OR+1=1-- and submit the request.

3. Observe the response and notice that now all products are displayed.



