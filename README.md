# E-Com

## Description

This project is a mock e-commerce website designed to showcase a range of products and provide a seamless shopping experience. Users can browse through products, view product details, add items to their cart, and view the cart contents via a convenient popover. During checkout, users can review their total cost, enter shipping details, and place orders, which are then stored in a database. The site features pagination to manage product listings effectively, displaying a set number of items per page

## Technologies Used

- **Frontend**: JavaScript, HTML, CSS, jQuery
- **Backend**: Django
- **Database**: SQLite (default database of Django)

## Features

- **Product Listings**: Browse a range of products with pagination to view a set number of items per page.
- **Shopping Cart**: Add items to a cart and view cart contents in a convenient popover.
- **Checkout Process**: Review total cost, enter shipping details, and place orders.
- **Order Management**: Orders are saved to the database for processing and tracking.

## Getting Started

To get a local copy of the project up and running, follow these steps:

### Prerequisites

Ensure you have the following installed:

- **Python**: Version 3.12
- **pip**: Python package installer

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Shawn1303/E-Com.git
   cd E-Com

2. **Set Up the Backend**
   
   - Create and Activate a Virtual Environment
      ```bash
      python -m venv .venv
      ```
      
      Activate the Virtual Environment:
     
      - On Windows:
        ```bash
        .venv\Scripts\activate
        
      - On macOS/Linux:
        ```bash
        source .venv/bin/activate
        
   - Install Django and Dependencies
     ```bash
     pip install -r requirements.txt
     
   - Run Database Migrations
     ```bash
     python manage.py migrate

   - Create a Superuser (Optional for Admin Access)
     ```bash
     python manage.py createsuperuser

   - Start the Django Development Server
     ```bash
     python manage.py runserver
