# beach-azon
Welcome to beach-azon! An amazon like app for purchasing your basic items for a fun outdoor experience! For creating this store front I did the following steps. First, created a MySQL Database called `beachazon`. I then made Table inside of that database called `products`. Within the products table the following columns were generated; item_id, product_name, department_name, price, and stock_quantity I filled the database with (10) various products that a customer going to the beach would be purchasing.

Next I created a node application where the customer would be interacticng with the storefront and making selections. Running `beachazon.js` will first display all of the items available for sale. Include the ids, names, and prices of products for sale.

When the customer enters the store they are prompted with two messages. 
1. Asking the customer the product in which they would like to purchase?
2. Asking the customer the quantity of the product they would like to purchase?

When the customer places the order on beachazon there are two options - either there will be enough in stock of that product for the customer to proceed with more orders (this updates the SQL databse to reflect the remaining qty), or the app will log that there is an 'Insufficient quantity', and the order cannot be placed.

Video demo here: https://drive.google.com/file/d/11ic3GlxBYY2hOwu8SwQLpe-gYVsq4wTx/view

