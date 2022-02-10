# E-Commerce-Back-End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will be beneficial as a full-stack developer.

E-commerce back end uses Express.js API and Sequelize to interact with a MySQL database. This application has API routes that allow a user to SELECT, INSERT, UPDATE, and DELETE data in three tables (categories, products, and tags).


<br>


## Links
<!-- 
Deployed App on Heroku
> [https://note-taker-elliotpark.herokuapp.com/](https://note-taker-elliotpark.herokuapp.com/)
<br> -->

Link to GIF of Application - GET routes 
> [https://drive.google.com/file/d/1-b9sKZIA8Pz4-CW6Co4tmYjEoUNh0QbL/view](https://drive.google.com/file/d/1-b9sKZIA8Pz4-CW6Co4tmYjEoUNh0QbL/view)
<br>

Link to GIF of Application - PUT, POST, and DELETE routes 
> [https://drive.google.com/file/d/1XVZE1bDq4WX2pvvH1lN1NoJW8ohasovM/view](https://drive.google.com/file/d/1XVZE1bDq4WX2pvvH1lN1NoJW8ohasovM/view)
<br>


Github Repository
> [https://github.com/elliotpark410/E-Commerce-Back-End](https://github.com/elliotpark410/E-Commerce-Back-End)

<br>


## Table of Contents
  * [Getting-Started](#getting-started)
  * [Installation](#installation)
  * [Technologies-Used](#technologies-used)
  * [Contribution-Guidelines](#contribution-guidelines)
  * [Cloning-Guidelines](#cloning-guidelines)
  * [Screenshots](#screenshots)
  * [GIF-of-Application](#gif-of-application)
  * [Code-Snippets](#code-snippets)
  * [Learning-Points](#learning-points)
  * [Authors](#authors)
  * [License-and-Acknowledgements](#license-and-acknowledgements)
  * [Contact](#Contact)

<br>


## Getting-Started

To begin the application, use the following in command line:

```bash
cd db
mysql -u root -p
exit

cd server.js
node seeds/index.js
node server.js
```
<br>


## Installation

1. You will need to install Node.js. Here is a link below:

>https://nodejs.org/en/download/

<br>

2. Once you have downloaded Node.js, you will want to download node package manager (npm). In command line, you can enter:

>npm install -g npm

<br>

3. After installing npm, you have to initialize npm. In command line, you can enter:

>npm init -y

<br>

4. Next, install Express which is node web framework. In command line, you can enter:

>npm install express

<br>

5. Next, install Sequelize which is a Node.js Object Relational Mapping (ORM) tool. In command line, you can enter:

>npm install Sequelize

<br>

6. Next, install dotenv which is a module that loads environment variables. In command line, you can enter:

>npm install dotenv

<br>

7. Next, install mysql2 which is one of the mysql APIs for node. In command line, you can enter:

>npm install mysql2

<br>

8. Additionally, you will need to download mysql database to store and access data:

>https://www.mysql.com/downloads/

<br>


9. Lastly, you will need to download Insomnia for testing API routes:

>https://insomnia.rest/download

<br>


<!-- ## Prerequisites
Requires node.js, npm inquirer, and npm jest (optional)

<br> -->


<!-- ## Test-Instructions

To test the API, I recommend downloading [Insomnia's API Platform](https://insomnia.rest/) and enter the following in Insomnia's URL:

>GET http://localhost:3000/api/notes

<br>

>POST http://localhost:3000/api/notes

Example POST body: 
```bash
{
  "title":"Notes Title",
  "text":"notes text content"
}
```
*id is automatically generated so you do not need to enter id

<br>
<br>

>DELETE http://localhost:3000/api/notes/:id

<br>

Example DELETE: The API request below will delete note with id = "1"
>DELETE http://localhost:3000/api/notes/1

<br> -->


## Technologies-Used

* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Node.js](https://nodejs.org/en/)
* [npm Express](https://www.npmjs.com/package/express)
* [npm Sequelize](https://www.npmjs.com/package/sequelize)
* [npm dotenv](https://www.npmjs.com/package/dotenv)
* [npm mysql2](https://www.npmjs.com/package/mysql2)
* [MySQL](https://www.mysql.com/downloads/)
* [Insomnia](https://insomnia.rest/download)


<br>


## Contribution-Guidelines
To contribute, please follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

<br>


## Cloning-Guidelines

To install this code, please use [Github's guidlines to clone the repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

<br>

Github repository:
>https://github.com/elliotpark410/E-Commerce-Back-End

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
<br>


## GIF-of-Application

<img src="Images\E-Commerce-GET-routes.gif" title="E-Commerce-GET-routes gif" width = 400px>

Link to E-Commerce-GET-routes GIF 
> [https://drive.google.com/file/d/1-b9sKZIA8Pz4-CW6Co4tmYjEoUNh0QbL/view](https://drive.google.com/file/d/1-b9sKZIA8Pz4-CW6Co4tmYjEoUNh0QbL/view)
<br>

<br>

<img src="Images\E-Commerce-PUT-POST-DELETE-routes.gif" title="E-Commerce-PUT-POST-DELETE-routes gif" width = 400px>

Link to E-Commerce-PUT-POST-DELETE-routes GIF 
> [https://drive.google.com/file/d/1XVZE1bDq4WX2pvvH1lN1NoJW8ohasovM/view](https://drive.google.com/file/d/1XVZE1bDq4WX2pvvH1lN1NoJW8ohasovM/view)
<br>

<br>

## Code-Snippets

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


## Learning-Points

* How to use Sequelize ORM

* How to modularize back-end applications 

* How to create API routes and models 

* How to use MySQL Workbench and Insomnia for testing API routes


<br>


## Authors
 **1. Elliot Park** 

[https://github.com/elliotpark410](https://github.com/elliotpark410)
<br>

[https://www.linkedin.com/in/elliot-park/](https://www.linkedin.com/in/elliot-park/)

<br>


## License-and-Acknowledgements

This project is licensed under the MIT license via UC Berkeley's Extension Program

<br>

Big acknowledgements and thank you to Jerome Chenette, Manuel Nunes, Vince Lee, and Hannah Folk for their support and guidance!

<br>


## Contact
If you'd like to learn more about my projects, check out my Github profile: [https://github.com/elliotpark410](https://github.com/elliotpark410)

<br>

If you have any questions, please don't hesitate to email me at [elliotpark410@gmail.com](mailto:elliotpark410@gmail.com)

<br>
Copyright (c) 2022 Elliot Park



 
  

 



 



