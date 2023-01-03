# E-commerce Back End

## Description
RESTful API for an e-commerce site built with Node.js, Express.js, MySQL2 and Sequelize.

## License  
This application is covered under the following license. Please review the link below for additional information pertaining to the license.
    
![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)  
https://www.gnu.org/licenses/gpl-3.0

## Table of Contents
[Built With](#built-with)  
[Installation](#installation)   
[Walkthrough Video](#walkthrough-video)  
[Contribution](#contribution) 

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
* Enter `npm install` in the CLI while in the root folder to install the required npm packages
* Create a .env file in the root folder and add the following lines to the file, filling in your unique MySQL password:

    `DB_NAME='ecommerce_db'`  
    `DB_USER='root'`  
    `DB_PASSWORD=''`  

* Enter `mysql -u root -p` in the CLI and enter your MySQL password to navigate to the MySQL Shell
* Enter `source db/schema.sql` in the MySQL Shell to create the `ecommerce_db` database
* Exit the MySQL Shell and enter `npm run seed` in the CLI to seed the database
* Enter `npm start` in the CLI to launch live server
* Routes can tested and database can be edited via an API development platform such as Insomnia

## Walkthrough Video
https://drive.google.com/file/d/1qrB9x0oaG5cgwK_jfNkfYvU6ni5PUq6q/view

## Contribution
Built by Dylan Hay