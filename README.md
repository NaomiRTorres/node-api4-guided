# Web API Deployment Challenge

Guided project for **Web API IV** module.

In this project we will learn how to deploy a Web API to `heroku`.

## Prerequisites

- Sign up for a [heroku](https://www.heroku.com/) free account.

## Instructions

Please fork this repository and follow along **using your fork** as the instructor deploys the API to `heroku`.


## NOTES
 ## DEPLOYING TO HEROKU
 - read the port from the environment: `const port = process.env.PORT`
 - define a `start` script in `package.json` that uses `node` (instead of `nodemon`) to run the server
    - by default heroky will run your application with `npm start`
 - 