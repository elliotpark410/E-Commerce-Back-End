# E-Commerce-Back-End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will be beneficial as a full-stack developer.

E-commerce back end uses Express.js API and Sequelize to interact with a MySQL database. This application has API routes that allow a user to SELECT, INSERT, UPDATE, and DELETE data in three tables (categories, products, and tags).


<br>

## Table of Contents
  * [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Technologies Used](#technologies-used)
  * [Screenshots](#screenshots)
  * [GIF of Application](#gif-of-application)
  * [Code Snippets](#code-snippets)
  * [Learning Points](#learning-points)
  * [Author](#author)

<br>


## Getting Started

To begin the application, use the following in command line:

```bash
cd db
mysql -u root -p
exit

cd ..
node seeds/index.js
node server.js
```
<br>


## Prerequisites

1. [Download Node.js](https://nodejs.org/en/download/)

<br>

2. Install node package manager (npm)

`npm install -g npm`

<br>

3. Install dependencies express, Sequelize, dotenv, and mysql2

`npm install`

<br>

4. [Download mysql](https://www.mysql.com/downloads/)

<br>


5. [Download insomnia](https://insomnia.rest/download)

<br>

## Technologies Used

* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Node.js](https://nodejs.org/en/)
* [npm Express](https://www.npmjs.com/package/express)
* [npm Sequelize](https://www.npmjs.com/package/sequelize)
* [npm dotenv](https://www.npmjs.com/package/dotenv)
* [npm mysql2](https://www.npmjs.com/package/mysql2)
* [MySQL](https://www.mysql.com/downloads/)
* [Insomnia](https://insomnia.rest/download)


<br>

## Screenshots 

<br>
Initializing MySQL database
<img src="Images\Initializing MySQL database screenshot.png" title="Initializing MySQL database screenshot" width = 650px>

<br>
<br>
Adding seed file to MySQL database
<img src="Images\Adding seed file to MySQL database screenshot.png" title="Adding seed file to MySQL database screenshot" width = 650px>

<br>
<br>
Starting Application
<img src="Images\Starting Application screenshot.png" title="Starting Application screenshot" width = 650px>

<br>
<br>
Insomnia GET route for http://localhost:3001/api/categories
<img src="Images\Insomnia GET route screenshot.png" title="Insomnia GET route screenshot" width = 650px>
<br>

<br>


## GIF of Application

<img src="Images\E-Commerce-GET-routes.gif" title="E-Commerce-GET-routes gif" width = 400px>
 
[E-Commerce-GET-routes GIF ](https://drive.google.com/file/d/1-b9sKZIA8Pz4-CW6Co4tmYjEoUNh0QbL/view)
<br>

<br>

<img src="Images\E-Commerce-PUT-POST-DELETE-routes.gif" title="E-Commerce-PUT-POST-DELETE-routes gif" width = 400px>

[E-Commerce-PUT-POST-DELETE-routes GIF](https://drive.google.com/file/d/1XVZE1bDq4WX2pvvH1lN1NoJW8ohasovM/view)
<br>

<br>

## Code Snippets

This code snippet shows how you can use sequelize.sync() to synchronize all models i.e. a table in your database

* sequelize.sync() creates the table if it doesn't exits and does nothing if it already exists

* sequelize.sync({ force: true }) creates the table and drops it first if it already exists

* sequelize.sync({ force: false }) creates the table. If the table exists, any field additions/modifications/deletions you have won't be executed

```
sequelize.sync({ force: false }).then(() => {
  app.listen(PORT, () => console.log(`Now listening on port http://localhost:${PORT}'`));
});
```

 <br>


## Learning Points

* How to use Sequelize ORM

* How to modularize back-end applications 

* How to create API routes and models 

* How to use MySQL Workbench and Insomnia for testing API routes


<br>


## Author
 **Elliot Park** 

[Github](https://github.com/elliotpark410)

<br>

[LinkedIn ](https://www.linkedin.com/in/elliot-park/)

<br>

[Email](mailto:elliotpark410@gmail.com)

