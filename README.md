## Object-Relational Mapping (ORM) Challenge: E-commerce Back End

### Description

*Build the back end for an e-commerce site. Take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.*


### App Demo

- Create Schema and Seed data
[![Ecom-schema & seed](https://img.youtube.com/vi/2wAEXB5b_J0/0.jpg)](https://youtu.be/2wAEXB5b_J0)


- GET,POST, PUT, and DELETE routes for categories
[![Ecom-categories](https://img.youtube.com/vi/Lo_zBiRr12s/0.jpg)](https://youtu.be/Lo_zBiRr12s)


- GET,POST, PUT, and DELETE routes for Tags
[![Ecom-tags](https://img.youtube.com/vi/eKGd7dZzNW8/0.jpg)](https://youtu.be/eKGd7dZzNW8)


- GET,POST, PUT, and DELETE routes for products
[![Ecom-products](https://img.youtube.com/vi/z09jZAMsdJc/0.jpg)](https://youtu.be/z09jZAMsdJc)



### User Story

```text
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### Acceptance Criteria

```text
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