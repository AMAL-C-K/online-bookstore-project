# Online Book Store

A Django-based online bookstore project with:

- User Authentication
- Book Listing
- Genre Filtering
- Search Functionality
- Pagination
- Sorting
- Shopping Cart
- Order Management
- Cash on Delivery (COD) Checkout

## Features

### Authentication
- User Registration
- User Login & Logout
- Session Authentication

### Book Management
- View All Books
- Genre-wise Book Filtering
- Single Book Detail Page
- Search Books by Title, Author, or Genre
- Sorting by:
  - A-Z
  - Price Low to High
  - Price High to Low

### Cart System
- Add to Cart
- Remove from Cart
- Update Quantity
- View Cart Total

### Order System
- Place Orders
- Order Summary

### Checkout
- Cash on Delivery (COD) Payment Method

## Tech Stack

- Django
- SQLite
- HTML
- CSS


## Run Project

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver