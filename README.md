# Felicity Pizza Online Shop

This is my first ever project, created in 2018, where I built a web application for ordering pizza online for my own pizza shop.

## Project Objective

The primary goal of this project was to facilitate the online sale of pizzas. This application features various forms to test different pizza varieties. It includes an HTML web-based interface and stores data in a relational database (MySQL). The application comprises multiple web pages with logical transitions using buttons or links.

## Features

When customers visit the website, they will find a top navigation bar with links to the following pages:
- **About Page**
- **Contact Page**
- **Create Order Page**
- **View Your Order Page**

### Create Order Page

On the Create Order page, users will find customer and order forms. Once a customer fills out and submits the form, the application performs the following actions:
1. **Customer Check**: 
    - **New Customer**: Adds the customer to the database and creates a new customer profile.
    - **Returning Customer**: Retrieves the customer's existing profile.
2. **Temporary Order Storage**: Stores a temporary order and provides options to keep, update, or delete the order.
3. **Order Confirmation**: 
    - Creates a new order in the database.
    - Retrieves the price for each item in the order.
    - Adds up the item prices to get the total price.
    - Assigns a unique order ID to the customer that can be used to get order details on the View Your Order page.

