# Udacity Full Stack Web Developer Nanodegree
# Final Project
Author: Mark Hebert


# Background:
-------------
This website is based on a similar website I built (http://LandToHunt.com). 
For simplicity sake, many of the features available on LandToHunt have been removed.


# Accessing the Website:
------------------------
This project can be accessed through the following IP Address: 45.55.196.243 
(http://45.55.196.243)

Server Access
-------------
The server can be accessed through SSH port 2200


# Software Insalled to Launch the Website:
------------------------------------------
It should be noted, this server was built using Ubuntu

NGINX
-----
Installation: sudo apt-get install nginx

NGINX is a free, open-source, high-performance HTTP server and reverse proxy, as 
well as an IMAP/POP3 proxy server. NGINX is known for its high performance, stability, 
rich feature set, simple configuration, and low resource consumption.

Gunicorn
--------
Installation: sudo pip install gunicorn
(python-pip package was previously installed - sudo apt-get install python-pip)

Gunicorn 'Green Unicorn' is a Python WSGI HTTP Server for UNIX. It's a pre-fork 
worker model ported from Ruby's Unicorn project. The Gunicorn server is broadly 
compatible with various web frameworks, simply implemented, light on server resources, 
and fairly speedy.


# Using the Website
-------------------
Viewing Properties:
-------------------
From the home page, you can see every property in the database. You can refine the 
results by category in the left column. Click on the property to view its details.

Logging In:
-----------
(This function is not available, as it requires connection over https to connect)
You must have a Google account to login. Use the button at the top right to login.

Logging Out:
------------
Logging out is similar to logging in. Use the button at the top right to log out.

Adding Properties:
------------------
Once you have logged in, a button in the top right of the page (Add Property) will 
appear. Click this button to add your property.

Edit and Delete Properties:
---------------------------
When you are logged int, buttons labeled 'Edit' and 'Delete' will appear below the 
properties you have created. You can only edit or delete propeties you have created.


# Resources
-----------
Gunicorn
http://gunicorn.org/

NGINX
https://www.nginx.com/resources/wiki/

Digital Ocean
https://www.digitalocean.com/

StackOverflow
http://stackoverflow.com/

LandToHunt.com
http://LandToHunt.com/
