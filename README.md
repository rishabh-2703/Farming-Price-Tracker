# Farmer Market Product Tracker 
Overview

The Farmer Market Product Tracker is a simple Python program designed to help users manage product information such as product names, market names, and rates. It provides a menu-driven interface through which users can add new products, view existing ones, update prices, delete entries, and view basic analytics. All data is stored in a text file (products.txt), ensuring that the information is preserved between program runs.

# Features

Add new products with name, market, and rate.
View all products stored in the system.
Search for specific products by name.
Update the rate of an existing product.
Delete products from the list.
View analytics such as minimum, maximum, and average rate.
Data is stored permanently in products.txt.


System Requirements
Python 3.7 or above.
Works on Windows, macOS, and Linux.
Does not require any external libraries.


How the Program Works
When the program starts, it attempts to load data from products.txt.
If the file does not exist or is empty, the program adds a default product to ensure the system is not blank.
The program then displays a menu with options for performing various operations.
Whenever the user adds, updates, or deletes a product, the file is updated automatically.

Menu Options
Add Product
View Products
Search Product
Update Product Rate
Delete Product
View Statistics
Exit Program


Possible Improvements
Add sorting features (by rate or name)
Provide exporting options (CSV or PDF)
Add a graphical user interface
Include date-based price history tracking
