# E-commerce Back End

## Description
RESTful API for an e-commerce site built with Node.js, Express.js, MySQL2 and Sequelize.

## License  
This application is covered under the following license. Please review the link below for additional information pertaining to the license.
    
![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)  
https://www.gnu.org/licenses/gpl-3.0

## Table of Contents
[Walkthrough Video](#walkthrough-video)  
[Built With](#built-with)  
[Installation](#installation)   
[Contribution](#contribution) 

## Walkthrough Video
https://drive.google.com/file/d/1qrB9x0oaG5cgwK_jfNkfYvU6ni5PUq6q/view

## Built With
* JavaScript
* Node.js
* Express.js
* MySQL2
* Sequelize
* dotenv
* Git
* Insomnia

## Installation
To run locally once cloned:
* Enter `npm install` in the command line while in the root folder to install the required npm packages
* Create a .env file in the root folder and add the following lines to the file, filling in your MySQL username and password:

    `DB_NAME='ecommerce_db'`  
    `DB_USER=''`  
    `DB_PASSWORD=''`  

* Enter `mysql -u root -p` and enter your MySQL password to navigate to the MySQL Shell
* Enter `source db/schema.sql` in the MySQL Shell to create the `ecommerce_db` database
* Exit the MySQL Shell and enter `npm run seed` in terminal while in the root folder of the project to seed the database
* Enter `npm start` in terminal to launch live server
* Routes can tested and database can be edited via an API development platform such as Insomnia

## Contribution
Built by Dylan Hay