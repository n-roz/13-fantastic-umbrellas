# E-commerce Back End Starter Code

## Description

This project is to build the back end for an online commerce store. We will use the Express.js API and use it with Sequelize to interact with a MySQL database.

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
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Installation
For this project you will need:

```npm init```

```npm install mysql2```

```npm install sequelize```

```npm install dotenv```

## Usage
When you are prompted, run the following command in your root folder:
```mysql -u root -p``` This opens the MySQL shell.
Enter your MySQL password when prompted. This can be edited in ```server.js```.
```source db/schema.sql;```
```quit;```
```npm run seed```
To invoke the application:
```npm start```

## Contributors and Questions