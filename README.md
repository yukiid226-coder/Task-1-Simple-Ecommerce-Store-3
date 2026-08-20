# Simple E-commerce Store — Task 1

A basic full-stack e-commerce website built with Django, HTML, CSS and JavaScript.

## Features
- Product listings
- Product details page
- Session-based shopping cart
- User registration, login and logout
- Checkout/order processing
- SQLite database for products, users and orders
- Django admin for managing products and orders

## Run locally

1. Install Python 3.10+.
2. Open a terminal in this folder.
3. Install dependencies:
   `pip install -r requirements.txt`
4. Run migrations:
   `python manage.py migrate`
5. Create an admin account:
   `python manage.py createsuperuser`
6. Start the server:
   `python manage.py runserver`
7. Open http://127.0.0.1:8000/

To add products, open http://127.0.0.1:8000/admin/ after creating the admin account.
