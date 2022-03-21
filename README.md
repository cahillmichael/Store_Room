# Store Room

## Description  
This application serves as the backend of an E commerce website. Users can populate a MySQL database with Categories, Products, and Tags. These elements can be modified and deleted.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Walkthrough](#walkthrough)

## Installation
This application requires MySQL2, express, sequelize, and dotenv to run. With the code cloned, run ```npm install``` in the root directory to install these dependencies. Your MySQL credentials will need to be added to a .env file in the root directory. Once this is done, open a MySQL shell and run the command ```source db/schema.sql```. This will drop and recreate the database. In you terminal, navigate to the root directory, and run the command ```npm run seed``` followed by  ```npm run start```. These will seed the database and start the server. For more information on MySQL2 or other dependecies, check out:
* https://www.npmjs.com/package/mysql2
* https://www.npmjs.com/

## Usage
Once the database has been seeded and the server started, you are free to explore the API endpoints with a tool of your choosing.

## Walkthrough
A video walkthrough is available here: [Walkthrough](https://d.pr/v/G68PoI)

