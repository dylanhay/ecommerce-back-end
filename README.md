# E-commerce Back End

## Description
Back end for an e-commerce site.

## Table of Contents
[Installation Instructions](#installation-instructions)   
[Built With](#built-with)  
[Walkthrough Video](#walkthrough-video)  
[Contribution](#contribution) 

## Installation Instructions
npm, Node.js, Express.js, MySQL, MySQL2, Sequelize, and dotenv must be installed to use this application.

* To initialize npm, enter "npm init" in terminal while in the root folder of the project
* Node.js can be downloaded and installed from https://nodejs.org/en/download/  
* MySQL can be downloaded and installed from https://dev.mysql.com/downloads/mysql/
* To install Express.js, MySQL2 and Sequelize, enter "npm install express sequelize mysql2" in terminal while in the root folder of the project
* To install the dotenv package, enter "npm install dotenv" in terminal while in the root folder of the project 

Once the above steps have been followed, follow the steps below to run the application: 
* Enter "mysql -u root -p" and enter your MySQL password to navigate to the MySQL Shell
* Enter "source db/schema.sql" in the MySQL Shell to create the "ecommerce_db" database
* Exit the MySQL Shell and enter "npm run seed" in terminal while in the root folder of the project to seed the data in the "seeds" folder to the database
* Enter "npm start" in terminal to launch live server

## Built With
* Node.js
* JavaScript

## Walkthrough Video
https://drive.google.com/file/d/1qrB9x0oaG5cgwK_jfNkfYvU6ni5PUq6q/view
## Contribution
Made with ❤️ by Dylan Hay