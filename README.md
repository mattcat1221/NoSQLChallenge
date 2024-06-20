# NoSQLChallenge


Part 1: Database and Jupyter Notebook Set Up
First I imported the data in establishments.json from my Terminal, named the database uk_food and the collection establishments.

The line of code that I used to import the data was: mongoimport --db uk_food --collection establishments --drop --file C:file:///Users/cmatthews/Downloads/establishments.json --jsonArray
I imported the PyMongo and Pretty Print libraries and created an instance of Mongo Client.

I confirmed that there was a uk_food database and assigned the database to a variable name. I confirmed that there was a establishments collection in the database and assigned the collection to a variable name.

Part 2: Update the Database
I created a dictionary for the restaurant Penang Flavours and used insert_one() to add it to the establishments collection.

I found the Business Type ID for Restaurant/Cafe/Canteen and updated Penang Flavours with its corresponding Business Type ID.

I created a dictionary for the restaurant Penang Flavours and used insert_one() to add it to the establishments collection.

I found the Business Type ID for Restaurant/Cafe/Canteen and updated Penang Flavours with its corresponding Business Type ID.

<img width="1634" alt="Screenshot 2024-06-19 at 9 48 10 PM" src="https://github.com/mattcat1221/NoSQLChallenge/assets/158774626/1b6d3877-e76c-4123-9ca6-982528b2f7fe">
