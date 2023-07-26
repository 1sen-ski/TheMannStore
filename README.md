# TheMannStore
My site for SoftUni Python Framework 2023

This project runs locally on your own machine, when installed. The requirements are in the requirements.txt file.
It is not hosted due to extreme Windows errors that prevent any hosting on AWS successful. Very unfortunate. 

The site has login/register/logout functionality.
A user can register and interact with the site. Edit his profile, send feedback to admins, order a product added by the admin, and other stuff.

A superuser can be created he has full control of everyone in the site, he can control everything from customized admin site(not visible to regular users) or django admin.

From Django admin the superuser can choose from ADMIN, STAFF, and CUSTOMER, if STAFF is chosen as a group for a user, he can control the orders, not the users.

When a user registers he is instantly put in the group CUSTOMER, so he cannot enter the admin site. 

See it for yourself, It's pretty cool.

It has no venv set up. Set a virtual env yourself. 



