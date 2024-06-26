# Inventory-Management-System

This project is an Inventory Management System implemented using MySQL. It allows users to manage product information, customers, orders, and other related data.


**Table of Contents :**

1.Installation
2.Database Structure
3.Functions and Procedures
4.Usage

**Installation**

1.Install MySQL: Ensure MySQL is installed on your system. Download MySQL.

2.Clone the Repository :                               git clone https://github.com/yourusername/inventory-management-system.git
                                                       cd inventory-management-system

3.Create and Set Up the Database :                     CREATE DATABASE inventory_management;
                                                       USE inventory_management;

4.Import the Database Structure and Sample Data :      mysql -u username -p inventory_management < inventory_management.sql


**Database Structure**

The database consists of the following tables:

product: Stores product information including price and associated provider.
provides: Stores discount information from different providers.
customer: Stores customer details.
select_product: Stores information about products selected by customers.

**Functions and Procedures**

Functions:
calculate_total_price(product_id INT): Calculates the total price for a given product, including discounts and taxes.
calculate_total_price_for_customer(cust_id INT): Calculates the total price for all products selected by a given customer.

Procedures:
show_all_products(): Displays all products along with their prices and discounts.






