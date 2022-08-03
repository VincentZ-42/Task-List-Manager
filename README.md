# Task List Manager: [Demo](https://secure-harbor-05512.herokuapp.com/users/signin)

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
| Sign In Page | ![sign in page](https://user-images.githubusercontent.com/49771001/182644376-e3dfb875-ef4e-4ceb-9af4-ffe6202457d4.png) |
| Developer Login View | ![developer login](https://user-images.githubusercontent.com/49771001/182644408-a586817b-41ab-4e72-9021-4cb7d29bafb3.png) |
| Viewing a Todo List | ![View Todo List](https://user-images.githubusercontent.com/49771001/182644442-cfcf385b-37cc-4ab8-aa57-36b0bef84ff1.png) |
| Creating a new Todo List | ![New List](https://user-images.githubusercontent.com/49771001/182644435-18da4b7f-d0ef-4c44-86fb-5c63999ae57c.png) |
| Admin Login View | ![Admin Login](https://user-images.githubusercontent.com/49771001/182644396-d87f3119-396e-41d0-bd89-238881a66c56.png) |


## Objectives
- Create a web application that can track task completion for various to-do lists for mutiple users
	- `Express.js` widely used to handling routing and HTTP requests
- Use relational database, PostgresSQL, to store user information
	- `PostgreSQL` allows us to associate specific data with certain users, allowing a more personal interface with the application  
- Deploy web application on Heroku
	- Deploying on Heorku allows our application to run on a cloud service, giving access to anyone in the public instead of forcing users to download code and running locally.

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