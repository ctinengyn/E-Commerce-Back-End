# E-Commerce-Back-End

<p align="center">
 <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/mySQL-blue"  />
</p>

## Description
This application is the creation of the backend for an E-Commerce website. Express.js was used for the server and MySQL for the database along with Sequelize as the ORM to run SQL models and queries. The SQL database includes tables for the products, categories, tags, and product tags. RESTful API ruotes are used to make requests and updates from the database which are joined through Sequelize queries.

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

## Example Links
- [Category Route](https://drive.google.com/file/d/1RUi6xNFBYwuea1XMZGVp80GuCfrQc8cs/)

## Installation
- Both Node.js and MySQL must be installed on your computer.
- Clone the repo by copying and pasting in your command line: 
  - `git clone git@github.com:ctinengyn/E-Commerce-Back-End.git`
- Navigate to the root directory and run: 
  - `npm install`
- To start the server, in the command line run: 
  - `npm start`

## Contact
- [Christine Nguyen](https://github.com/ctinengyn)
- ctine.ngyn@gmail.com