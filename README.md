## E- Commerce

## Walk trough


## User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria

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

## Instructions to run application

create an .env file with the following

- DB_NAME='ecommerce_db'
- DB_USER='root'
- DB_PW'xxx'

Open the terminal and install your dependencies with 

- npm i

run MySQL in the terminal with

- source db/shema.sql;
- show databases;
- quit;

Once you are out of mysql in the terminal you'll need to run the seeds with the next command

- npm run seed

The application is ready for the final step

- npm start