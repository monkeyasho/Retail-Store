# Retail-Store
## Overview
This project simulates a retail store database using SQL. The database models a typical retail store's operations, including the management of products, customers, orders, inventory, and employees. The project showcases the ability to design, implement, and query a relational database to support the various aspects of a retail store's operations.
## Database Structure
### Customers & Customer Accounts:

customers: Stores customer login details (user_id and password).
customer_accounts: Links customers to their bank account details.
### Orders:

customer_orders: Stores order details including the customer who made the order and the payment information.
order_items: Tracks items within each order, including supplier details and pricing.
Products & Classes:

items: Lists all products available for sale.
class: Categorizes products into different classes with a price cap and type (A, B, C).
Suppliers:

suppliers: Stores information about suppliers.
supplier_items: Links suppliers with the items they provide, including commission, discounts, stock levels, and reviews.
Preference Index:

preference_index: Stores calculated preference values for supplier items based on commission, reviews, and discounts.
The Calculate_preference_index function computes this value, and a trigger updates it whenever the supplier item data changes
