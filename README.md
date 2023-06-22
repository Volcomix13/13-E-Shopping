# 13-E-Shopping

## Description

This project was created to build an e-commerce site. This project also helped me understand SQL and express better.
The challenges I encountered were mainly learning how to create the correct routes and set up the dotenv file correctly.


## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation
Run the following commands in your terminal to install all the needed packages to run this app:
1. npm install the following: dotenv, express, mysql2, and sequelize

Once all the packages are installed, create a .env file and add your own credentials
Run the following command to start mySQL: mysql -u root -p and log in with your SQL credentials

## Usage

Once all the packages are installed,
1. Run the following command to start mySQL: mysql -u root -p and log in with your SQL credentials
2. Run command source db/schema.sql
3. Then you can close out SQM by typing command quit
4. Run command npm run seed
5. Run command node server.js, this will start the application by provising an active port
6. Open Insomnia and choose your express method (get/put/post/delete) followed by localhost:3001/api. You can add the route you wish to test by adding the name of the route after api. See example below.

    
![Image](./assets/image.png)
    

Repo link: https://github.com/Volcomix13/13-E-Shopping

## License
Please see repository for license info.