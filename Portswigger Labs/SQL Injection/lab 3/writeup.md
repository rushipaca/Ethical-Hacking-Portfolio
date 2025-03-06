## Description:

This lab contains a SQL injection vulnerability in the login function.

To solve the lab, perform a SQL injection attack that logs in to the application as the administrator user.


## Steps to Exploit:

1. Identify the part of request used to display the products.

2. Modify the category parameter, giving it the value '+OR+1=1-- and submit the request.

3. Observe the response and notice that now all products are displayed.



