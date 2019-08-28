# MongoDB-CRM-System

This is an application made for a school project.
The application is a CRM system for a fictional coffeeshop company. 
It has crud functionallity for employees, products, customers and orders. 
It has a login system that unlocks certain CRUD capabilities based on the employees position.
It also has a search function for employees, products, customers and orders.
The application can manage multiple coffee shops and can also manage the opening of new coffee shops.

This is only a prototype and should NOT be used in production.

Requirements:
MongoDB
Visual studio

At startup the application will create the database, some collections and will create documents in most collections. It will also create a login for "admin" "admin" which has full access to the system functionallities. Comment out "addStuffToDB()" on line 37 in Database.cs after first startup to avoid clones in the collections.
