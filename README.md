DJANGO E-COMMERCE PROJECT

To run the project:
install virtualenv
fork the code and on the root folder, type source env/bin/activate (for mac cmd)
run pip3 install -r requirements.txt (for max)
on cmd, run python manage.py runserver

DESCRIPTION

Majority of functionality only applied to ATX Jeans product

Implemented a fully functional ecommerce website,  shopping cart functionality, product gallery, rating/review system, receipt functionality

Implemented a login system that requires a verification link to be clicked for the account to be active, as well as a change password functionality
Implemented paypal payment gateway, and a secure way to pay using credit/debit card.

Utilized python decouple to store website’s sensitive information

Implemented secure django admin portal using honeypot

Logs out inactive user using django session timeout, which logs out after 1 hour of inactivity
