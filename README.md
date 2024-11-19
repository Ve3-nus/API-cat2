# API-cat2
# Project Django Project

## Setup Instructions

1. **Install dependencies:**
   Make sure you have `Python` and `pip` installed. Install the required dependencies by running:

   `(pip install -r requirements.txt)`
Set up the database: If you're using SQLite (default), you don't need to do anything extra.

Run migrations: After setting up the project, run the following command to create the necessary tables in the database:
 `(python manage.py migrate)`
 
Create a superuser (optional): To access the Django admin panel, create a superuser by running:
`(python manage.py createsuperuser)`
Run the server: Start the development server with the following command:
`(python manage.py runserver)`
Visit http://127.0.0.1:8000 to see the application in action.

## GitHub Repository
This repository includes the Django models for managing customers and orders. The Customer and Order models have a one-to-many relationship, where each customer can have multiple orders, but each order belongs to only one customer.

