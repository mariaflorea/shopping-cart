# Project overview
Develop a Shopping Cart application that allows users to add items to their cart, update quantities, and checkout. The application should handle concurrent access to the cart and ensure data consistency using transaction management. 
It should also include a simple front-end using Angular.

# Functional Requirements

<b>User Management (optional?)</b>

Users should be able to register and log in.
User data should be stored in the database.

<b>Product Management:</b>

Display a list of available products.
Each product should have a name, description, price, and stock quantity.

<b>Shopping Cart:</b>

Users can add products to their cart.
Users can update the quantity of items in their cart.
Users can remove items from their cart.
Display the total price of the items in the cart.

<b>Checkout Process:</b>

Users can proceed to checkout.
The application should handle stock validation and update the stock quantity accordingly.

<b>Transaction Management:</b>

Use Spring's transaction management to ensure data consistency.

<b>Multi-threading:</b>

Demonstrate handling of concurrent requests to the shopping cart using multi-threading.
Non-Functional Requirements

<b>Database Support:</b>

Use either Oracle or PostgreSQL.
Use Hibernate for ORM.

<b>Security:</b>

Implement basic authentication and authorization.
Secure sensitive data.

<b>Front-End:</b>

Use Angular to create a simple user interface for the shopping cart.
