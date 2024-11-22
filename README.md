# project overview
Develop a Shopping Cart application that allows users to add items to their cart, update quantities, and checkout. The application should handle concurrent access to the cart and ensure data consistency using transaction management. 
It should also include a simple front-end using Angular.

# Functional Requirements
User Management (optional?)

Users should be able to register and log in.
User data should be stored in the database.

Product Management:

Display a list of available products.
Each product should have a name, description, price, and stock quantity.

Shopping Cart:

Users can add products to their cart.
Users can update the quantity of items in their cart.
Users can remove items from their cart.
Display the total price of the items in the cart.

Checkout Process:

Users can proceed to checkout.
The application should handle stock validation and update the stock quantity accordingly.
Ensure that the checkout process is atomic and handles concurrent access.

Transaction Management:

Use Spring's transaction management to ensure data consistency.
Implement optimistic locking to handle concurrent updates to the cart --> shall we give this hint or let them come up with the solution?

Multi-threading:

Demonstrate handling of concurrent requests to the shopping cart using multi-threading.
Non-Functional Requirements

Database Support:

Use either Oracle or PostgreSQL.
Use Hibernate for ORM.

Security:

Implement basic authentication and authorization.
Secure sensitive data.

Front-End:

Use Angular to create a simple user interface for the shopping cart.
