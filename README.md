# TheMannStore
My site for SoftUni Python Framework 2023

In short, it's a shopping site. The admins add products to their main page, and registered users can purchase these items. They purchase the item by adding to their cart, checking out with fake credit card, and then they can watch the status of their ordered items. The Admin changes the status, is it delivered, is it pending etc..

This project runs locally on your own machine, when installed. The requirements are in the requirements.txt file.

The site has login/register/logout functionality.
A user can register and interact with the site. Edit his profile, send feedback to admins, order a product added by the admin, and other stuff.

A superuser can be created he has full control of everyone in the site, he can control everything from customized admin site(not visible to regular users) or django admin.

From Django admin the superuser can choose from ADMIN, STAFF, and CUSTOMER, if STAFF is chosen as a group for a user, he can control the orders, not the users.

When a user registers he is instantly put in the group CUSTOMER, so he cannot enter the admin site. 

See it for yourself, It's pretty cool.

It has no venv set up. Set a virtual env yourself. 

Thanks to https://github.com/TheRealStemarMan <- for the Front End part. Huge HTML and CSS help. The backend python part is entirely from me.



