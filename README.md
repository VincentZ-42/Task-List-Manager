# Task List Manager

# Table of Contents
- [Description](#description)
- [Usage](#usage)
- [Images](#images)
- [Objectives](#objectives)
- [Technologies Used](#technologies-used)
- [References](#references)

## Description
Task List Manager is a web application that allows users to create multiple lists of tasks and track their completion. Each list and task is unqiue to the user. This application is an upgrade of [To-Do List Tracker](https://github.com/VincentZ-42/LaunchSchool/tree/main/js175/todo), which now includes the implementation of PostgreSQL as the database to persist data and deployed on Heroku.  

## Usage
- Click on [Demo](https://secure-harbor-05512.herokuapp.com/users/signin)
- Sign in with either credentials

| username | password |
| :-: | :-: |
| admin | secret |
| developer | letmein |

- Navigate with interface available (See [Images](#images) Section)
	- Click on the any list to view tasks
	- Click on the check box to mark or unmark complete
	- CLick on trash button to delete task
	- Click on Complete All button to mark all tasks complete
	- click on New List to create a new to-do list
	- Click on Edit List to rename to-do list or delete entire list

## Images

| Feature | Image |
| :-: | :--: |
| Sign In Page | ![sign in page](https://user-images.githubusercontent.com/49771001/183760611-c52e3482-fd24-4c5a-8f3c-a3464d9731ca.png) |
| Developer Login View | ![developer login](https://user-images.githubusercontent.com/49771001/183760624-458cd37f-31ad-4f8d-94fb-e082afd0b7ee.png) |
| Viewing a Task List | ![View Task List](https://user-images.githubusercontent.com/49771001/183760633-b479086b-f4ea-495e-bd0d-6a44f41e92b5.png) |
| Creating a new Task List | ![New List](https://user-images.githubusercontent.com/49771001/183760639-59a324fd-3873-4c07-8f2b-9d933225df99.png) |
| Admin Login View | ![Admin Login](https://user-images.githubusercontent.com/49771001/183760645-638046b5-e2bf-4e24-9ce3-65b13e2e0e26.png) |


## Objectives
- Create a web application that can track task completion for various to-do lists for mutiple users
	- `Express.js` widely used to handling routing and HTTP requests
- Use relational database, PostgresSQL, to store user information
	- `PostgreSQL` allows us to associate specific data with certain users, allowing a more personal interface with the application  
- Deploy web application on Heroku
	- Deploying on Heroku allows our application to run on a cloud service, giving access to anyone in the public instead of forcing users to download code and running locally.

## Technologies Used
- Pug as template engine
- Express.js as backend
- PostgreSQL as Database
- Heroku as Cloud Platform to host application
- Visual Studio Code as IDE

## References
- Launch School Course: JS185
- Heroku: https://devcenter.heroku.com/categories/reference
- Pug: https://pugjs.org/language/inheritance.html
- Express: https://expressjs.com/
- PostgreSQL: https://www.postgresql.org/docs/

## Future implimentations
- Integrate Google sign-in
