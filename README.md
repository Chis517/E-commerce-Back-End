# E-commerce-Back-End

## Description

This application uses the Express.js API, configured by Sequelize to interact with a MySQL database to run the back end of an e-commerce site!

This back end will have your e-commerce company website compete with the rest!

* Keep your database organized sorting your product with catagories and relevant tags!
* Create, Update, or Delete products as needed to keep your prices and stock up to date!


## Installation

[SSH of repo]
git@github.com:Chis517/E-commerce-Back-End.git

1. Clone the GitHub repo with the key above in your command line
2. Run npm i or npm install to download the packages required to run the application.
3. Create a .env file and add the following to your new file:
  DB_NAME='ecommerce_db'
  DB_USER='your-user'
  DB_PW='your-password'
  * Note: You will need to enter your MySQL credentials for the values of DB_USER and DB_PW
4. Run mysql in the command line and enter the following:
  * USE ecommerce_db
  * source db/schema.sql;
5. In a seperate command line window, run npm start to start your application


## Technologies

* JavaScript
* Node.js
* Express
* MYSQL
* Sequelize
* dotenv


## URL Link and demo

* [URL of repo]
(https://github.com/Chis517/E-commerce-Back-End)

* [URL of video demo]
(https://watch.screencastify.com/v/F2ruyAeJ0bUT89bGPuRf)