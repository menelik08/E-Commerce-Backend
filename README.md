# E-Commerce Backend

## Description 

This app is the backend portion of an E-Commerce website. Express.js was used for the server and MySQL for the database along with Sequelize as the ORM to run SQL models and queries. The SQL database includes tables for products, categories, tags, and product tags. RESTful API routes are used to make requests and updates from the database which are joined through Sequelize queries.

Link to the demo video : 

## Features 

⚡️ `dotenv` to load environment variables from a .env file into `process.env` and store configuration in the environment separate from code \
⚡️ `mysql2` module to connect to MySQL database and perform queries\
⚡️ `express.js`and `sequelize` to build api routes GET (Select All), GET by id (Select by ID), POST (Create), PUT (Update), DELETE (Destroy)


## Usage 


This application is running under mysql as a local host, you can modify the .env file with your own user/password to start the application.

After installation :
- Creat, Sync and Seed data: 
    - run `mysql -u root -p` in terminal and use password to login to your mysql shell
    - `source db/schema.sql` in mysql shell
    - `npm run seed` in terminal
- Functionality:
    - `npm start`in terminal to start the server
    - use [Insomnia](https://insomnia.rest/download) to interact through different routes.

## Technologies 

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Express.js](https://expressjs.com/)
* [Node.js](https://nodejs.org/en/)
* [MySQL](https://www.mysql.com/)
* [dotenv](https://www.npmjs.com/package/dotenv)
* [Sequelize](https://sequelize.org/)


