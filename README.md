# E-Commerce Back End


## Description

The E-Commerce Back End is an app that will allow the user to do the following:
- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia Core for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
- THEN I am able to successfully create, update, and delete data in my database


## Installation
    Make .env file and structure like:
    - `DB_NAME='ecommerve_db'`
    - `DB_USER='root'`
    - `DB_PW='YOURPASSWORD'`
     


    In bash install dependancies 
    - `npm init`
    - `npm install express`
    - `npm install sequelize`
    - `npm install mysql2`
    - `npm install dotenv`
    

## Usage

Enable mysql shell
- `mysql -u root -p`
- Enter your password for mysql
- `source db/schema.sql`


Seed database in bash
 `npm run seed`.

Run the server
 `npm start`. 
 
Use Insomnia Core to check routes
    
