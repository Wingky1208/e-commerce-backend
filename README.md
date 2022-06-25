# e-commerce-backend

Internet retail, also known as e-commerce, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. The goal of this project was to understand the fundamental architecture of these platforms.

The E-Commerce Backend is a REST API for an internet retail website. The API is built onto an Express.js server that uses Sequelize to interact with a MySQL database. Sequelize is a promise-based Node.js ORM(Object Relation Mapping) for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server.

This E-Commerce backend has the API routes that point to each of the standard CRUD operations for each data group. The routes can be used to:

Create categories, products, tags
View categories, products, tags
Establish associations between the different entities
Update categories, products, & tags
Delete entries from the database


## Seed the Database and Category walkthrough video:
https://drive.google.com/file/d/1GkB9kJ2X7gCaCnpjWAbYyfh8hYOzaM_F/view

## Products walkthrough video:
https://drive.google.com/file/d/1Mqcz1RjWKAzhl0uGeW-plisBP-CchNuC/view

## Tag walkthrough video:
https://drive.google.com/file/d/1Rx5Ex960bEAek9V0nct5KljMvSFq2WTq/view


## Usage

This section assumes you have installed the application, and created the .env file in the root directory.

To finish the set-up the application, complete the following steps:

1.Create a MySQL database on your local machine using the schema.sql file located in the /db/ directory(From the MySQL CLI, source db/schema.sql)
2.Seed the database with sample data to be used for testing purposes(Run npm run seed from inside the root directory of the project)
Now you're ready to start the application! You can start the server by running:

npm start

The server is running, now you can make requests to it through your desired method. If you're new to the backend, I suggest trying out Insomnia.

## Screenshot

![image](https://user-images.githubusercontent.com/100000900/175779493-45ad3567-07af-4f03-98e8-a18763daba60.png)




