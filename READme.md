Project Title
E-Commerce Back End

#Description

This is a working back end of a retail E-comerce website.


#Installation Instructions

The application runs on a node.js command line. Run npm install and updtae your environment variables for your mySQL credentials.

Node.js
Use theMySQL2 NPM package to connect to your MySQL database and perform queries.
Sequelize packages to connect your Express.js API to a MySQL database and the
dotenv package to use environment variables to store sensitive data.
After creating the models and routes, run npm run seed to seed data to your database so that you can test your routes.
Create the code needed in server.js to sync the Sequelize models to the MySQL database on server start.
To install the required dependencies, please run the following command:

npm i mysql2
npm i sequelizer

Walkthrough Video:

https://www.hippovideo.io/video/play/dyVeFmQcPWLqn4jrt9PczHOfF5YeSDBWXP8nRGDg3CU?utm_source=hv-campaigns&hreferer=private&_=1616872047586&
Watch Video

Mock-Up
The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia Core:

In Insomnia Core, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia Core:

In Insomnia Core, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia Core:

In Insomnia Core, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”

this walkthrough video should also show the POST, PUT, and DELETE routes for products and tags being tested in Insomnia Core.

License
badge

This project uses the MIT license.

Questions
Github Profile : [Creator]:(https://github.com/smurphy823)

If you have any questions please email me at stephaniemurphy588@yahoo.com