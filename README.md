Description

This is a supermarket management system developed in Python, designed for inventory, cash register, and sales management in a small market environment. The program enables product registration, handles sales transactions, monitors low stock and expiration dates, and provides a text-based interface for user interaction.

Features

1-Cash Register Management
.Allows opening and closing of the cash register with an initial balance input, automatically updating the total balance after each sale.

2-Product Management
.Add products to the inventory by entering details like code, name, price, quantity, category, expiration date, and warranty.

3-Search for products by code and display full details.
.Remove products from the inventory using their code.

4-Sales Processing
.Customers can add products to a sale, specifying quantity, with live checks for stock availability.
.Duplicate items in a sale are consolidated, updating their quantities and total prices dynamically.
.Displays a running total of the sale amount with each item added to the cart.

5-Inventory Control
.Lists products that are close to their expiration dates.
.Identifies low-stock products (fewer than 5 units).

6-Simple Text Interface
Command-line interface that allows users to choose options like opening/closing the register, managing products, and performing sales.

-Technologies Used

Python: The main programming language used for system development.

Object-Oriented Programming: Utilizes classes to represent items, the market, and inventory.

Code Structure

Item: Represents each product in the system with details such as code, name, price, quantity, type, expiration date, and warranty.

Store (Loja): Handles product inventory, manages cash register operations, processes sales, and provides inventory status reports.

Possible Future Improvements

Data Persistence: Add functionality to save inventory and sales data to files or a database to retain information after program closure.
Improved User Interface: Develop a graphical interface using libraries like Tkinter for easier interaction.
Enhanced Sales Reports: Add functionalities for generating reports on sales trends, top products, and inventory alerts.
