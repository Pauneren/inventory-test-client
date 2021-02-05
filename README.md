# Backend and Infrastructure
## Module 5 group project for Web development in Reykjavik Technical School

For this project our group used the FARM stack (FastAPI, React, MongoDB)
> [Project Back-end](https://github.com/iriselva/Inventory)

We started with the FastAPI Swagger and connected it to a database in MongoDB. The database is then hosted on Heroku. We also created simple example frontend with React. In the application you can create a user and login. The loggin will give you an authenication token to secure your account. After loggin in you can create your own inventory database, list the items, delete and update.

## Creative Inventory API

The inspiration for this web application is for creative people and artist to have an online place to organize and keep inventory of their creations. 

In the future we want to add more security and a better front-end infrastructure to hande all of the database objects. 

## Front End - Source Origins

This React Application is heavily influenced by Maximilian Schwarzmüller and his Udemy course, React, NodeJS, Express & MongoDB - The MERN Fullstack Guide: https://www.udemy.com/course/react-nodejs-express-mongodb-the-mern-fullstack-guide/

The source structue and especially then handling of authentication and storing of JWT token is borrowed from Max. However the application is of course modified as needed to meet our project's goals.
## Front End - Points of interest 
Points of interest here are mainly found in three source files, the api-helper.js which handles in one location all communication with the backend API, the NewItem.js where new items are created and ItemList.js which lists all items that belong to the logged in user. These files are the only ones that include any code comments as other things are not of importance here and those are explained very well in the Udemy course.

We hope you like it!

## Files
+ [App.js](src/App.js)
+ [Src folder](src)
+ [Components](src/item/components)

## Front-end
We have two frontends in process on Github
+ [Frontend Test Client repository](https://github.com/Pauneren/inventory-test-client) LIVE!
+ [Creative Inventory Frontend repository](https://github.com/iriselva/inventory-frontend)

## Live version
Link to the live verion of the web application (Heroku)
>  [Creative Inventory](https://inventory-test-client.herokuapp.com/)

## Recources
This project was made with:
+ VS Code
+ Python
+ MongoDB
+ FastAPI
+ React
+ Heroku
+ Trello
+ And more..

## Creators
Made with love by these talented Web development students!
+ [Iris Elva Olafsdottir](https://github.com/iriselva)
+ [Kolbrun Jonsdottir](https://github.com/kollaaj)
+ [Paula Nerenberg](https://github.com/Pauneren)


---
