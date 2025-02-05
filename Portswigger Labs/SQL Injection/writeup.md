## Description:

This lab contains an OS command injection vulnerability in the product stock checker.

The application executes a shell command containing user-supplied product and store IDs, and returns the raw output from the command in its response.

We must display the current user to solve the lab


## Steps to Exploit:

1. Identify the vulnerable parameter (in this case it is the storeID parameter)

2. Modify the storeID parameter, and give it whoami command to display current user

3. Observe the current user.



