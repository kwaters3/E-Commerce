# E-commerce

[![License](https://img.shields.io/badge/License-MIT-turquoise.svg)](https://opensource.org/licenses/MIT)

## Description

The main objective of this project is to gain a thorough understanding of the underlying structure of e-commerce platforms. This application was developed as a back end for an e-commerce website that uses the latest technologies and allows the user to compete with other e-commerce businesses, with the manager of an online retail company as the target user. This e-commerce application uses object-relational mapping (ORM) and has a modified back end starter code. Additionally, its working Express.js API is configured to use Sequelize as the WORM that interacts with the MySQL database, which consists of tables for categories, products, tags, and product tags. RESTful API routes point to each standard Create, Read, Update, and Delete (CRUD) operation to make requests on the database.

## Table of Contents

- [Description](#description)
- [Visuals](#visuals)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Credits](#credits)
- [Future-Development](#future-development)
- [License](#license)
- [Questions](#questions)

## Visuals

#### Click on the image below to reveal the video walk-through of the `installation` process:

[![Screenshot](./assets/images/screenshot1.png)](https://drive.google.com/file/d/1QbotX_8gA8kMAfb2h3Fc35aLuqua1c3N/view)

#### Click on the image below to reveal the video walk-through of the `category-routes` process:

[![Screenshot](./assets/images/screenshot1.png)](https://drive.google.com/file/d/1QbotX_8gA8kMAfb2h3Fc35aLuqua1c3N/view)

#### Click on the image below to reveal the video walk-through of the `product-routes` process:

[![Screenshot](./assets/images/screenshot1.png)](https://drive.google.com/file/d/1QbotX_8gA8kMAfb2h3Fc35aLuqua1c3N/view)

#### Click on the image below to reveal the video walk-through of the `tags-routes` process:

[![Screenshot](./assets/images/screenshot1.png)](https://drive.google.com/file/d/1QbotX_8gA8kMAfb2h3Fc35aLuqua1c3N/view)



## Installation

#### How to install the application:

- First, clone the git repository from [GitHub](https://github.com/kwaters3/E-Commerce) 
    - Open the clone file in VS code or in your terminal 
    - Create your` .gitignore` and `.env` files.
    - Check the `dependencies` and `dev-dependencies` that are needed on `package.json`.
- Next, set up all the existing npm packages, run `npm init`.

- Then, install the required dependencies on the `node_modules` folder, run: `npm install`.

- Then, to create your database, go to the terminal and run: `mysql -u root -p`. 
  - Enter mysql password when prompted.
  - Next, enter `source db/schema.sql`. 
  - Then, to seed the database, run: `npm run seed`.

- Use MySQL Workbench, to confirm if the tables were created and the database was seeded. 

- To invoke the application, run: `npm start`. The Sequelize models sync to the MySQL database when the server starts. 

- To test the application, use `Insomnia` or `Postman` (view Test section).


## Usage

#### How to use the application:

- First, make sure to install the given application following the previous steps and video walkthrough. 

-  Next, on MySQL Workbench, click the connection for the application. 

## Dependencies


- [express](https://www.npmjs.com/package/express)
- [mysql2](https://www.npmjs.com/package/mysql2)
- [sequelize](https://www.npmjs.com/package/sequelize)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [nodemon](https://www.npmjs.com/package/nodemon)

## Credits

- [SQL - W3Schools](https://www.w3schools.com/sql/sql_intro.asp)
- [MySQL - W3Schools](https://www.w3schools.com/mysql/mysql_sql.asp)
- [Sequelize](https://sequelize.org/)


## License

This project is covered under the following license: <br/>
[![License](https://img.shields.io/badge/License-MIT-turquoise.svg)](https://opensource.org/licenses/MIT)

## Questions

If you have any questions, please email me at: knickler3@gmail.com <br/>
My GitHub page is: [kwaters3](https://github.com/kwaters3)
