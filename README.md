# E-commerce Back End

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description

This application replicates the back end of an e-commerce site. The working Express.js API has been configured to use Sequelize in order to interact with a MySQL database.

## User Story
```
AS A manager at an internet retail company  
I WANT a back end for my e-commerce website that uses the latest technologies  
SO THAT my company can compete with other e-commerce companies  
```

## Acceptance Criteria
```
GIVEN a functional Express.js API  
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file  
THEN I am able to connect to a database using Sequelize  
WHEN I enter schema and seed commands  
THEN a development database is created and is seeded with test data  
WHEN I enter the command to invoke the application  
THEN my server is started and the Sequelize models are synced to the MySQL database  
WHEN I open API GET routes in Insomnia Core for categories, products, or tags  
THEN the data for each of these routes is displayed in a formatted JSON  
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core  
THEN I am able to successfully create, update, and delete data in my database  
```

## Installation

The MySQL2 and Sequelize packages need to be installed to connect the Express.JS API to a MySQL database. The dotenv package should also be installed to use environment variables to store sensitive data.  

Run ```npm i``` to install these dependencies.

## Usage

Update credentials in the .env file. input MySQL username and password in the mysql.createConnection to properly connect the database to the API. 

Connect to MySql by running ```mysql -u root -p``` in the db. Enter your password when prompted.  
 
Then execute the schema by running ```source schema.sql```.  

Outside of the db, run ```npm run seed``` followed by ```npm start```.   

## Testing

Using Insomnia Core, all API routes should be tested. 

## Demo

The walkthrough video below demonstrates the application's API routes being tested in Insomnia Core.


## License

This application is covered by [MIT License](https://choosealicense.com/licenses/mit/).
