# MERN Expense Tracker

This project is an expense tracking application with data visualization - developed using React, Node, Express, MongoDB and Victory.

## Pictorial View of the Application

![MERN Expense Tracker](https://mernbook.s3.amazonaws.com/git+/expensetracker.png "MERN Expense Tracker")

![MERN Expense Tracker Graphs](https://mernbook.s3.amazonaws.com/git+/graphs.png "MERN Expense Tracker Graphs")
<!-- ### [Live Demo](http://skeleton.mernbook.com/ "MERN Skeleton") -->

## Application Features
- Track day-to-day expenses
- Adding expense records with details such as expense description, category, amount & incurred or paid expense
- visualizing expense data over time

#### I am also currently doing refactoring of the application and improving more on the design and functionality.

<!-- ### The application is also fully deploy and hosted on Heroku. Live view of the application Demo can be found here- [MERN Expense Tracker](https://) -->

## How to use the application

## Table of Contents
- [Getting Started](#getting-started)
  - [Tools Required](#tools-required)
  - [Installation](#installation)
- [Development](#development)

- [Running the App](#running-the-app)
- [Deployment](#deployment)
- [Authors](#authors)

## Getting Started

The project has two branches: `main`, `dev`.

* `main` contains the full source code on the solution I have developed for this project
* `dev` contains code under development and refactoring

## Project Folder Structure

```
  project-title
  ├── README.md
  ├── package.json
  ├── yarn.lock
  ├── nodemon
  ├── .babelrc
  ├── .gitignore
  ├── template
  ├── client
  │   ├── assets
  |   |   ├── images
  │   ├── auth
  |   |   ├── api-auth.js
  |   |   ├── auth-helper.js
  |   |   ├── PrivateRoute.js
  |   |   ├── Signin.js
  |   ├── core
  |   |   ├── Home.js
  |   |   ├── Menu.js
  |   ├── expense
  |   |   ├── api-expense.js
  |   |   ├── DeleteExpense.js
  |   |   ├── ExpenseOverview.js
  |   |   ├── Expenses.js
  |   |   ├── NewExpense.js
  |   ├── report
  |   |   ├── CategoryPie.js
  |   |   ├── MonthlyScatter.js
  |   |   ├── Reports.js
  |   |   ├── Yearly.js
  |   ├── user
  |   |   ├── api-user.js
  |   |   ├── DeleteUser.js
  |   |   ├── EditProfile.js
  |   |   ├── Profile.js
  |   |   ├── Signup.js
  |   |   ├── Users.js
  |   ├── App.js
  |   ├── main.js
  |   ├── MainRouter.js
  │   └── theme.js
  ├── config
  |   ├── config.js
  ├── server
  |   ├── controllers
  |   |   ├── auth.controller.js
  |   |   ├── expense.controller.js
  |   |   ├── user.controller.js
  |   ├── helpers
  |   |   ├── dbErrorHandler.js
  |   ├── models
  |   |   ├── expense.model.js
  |   |   ├── user.model.js
  |   ├── routes
  |   |   ├── auth.routes.js
  |   |   ├── expense.routes.js
  |   |   └── user.routes.js
  |   ├── devBundle.js
  |   ├── express.js
  |   └── server.js
  ├── webpack.config.client
  ├── webpack.config.client.production
  └── webpack.config.server
```

### Tools Required
The following tools required to develop and run this application:

* A text editor (like VS Code) or an IDE
* Command Line

### Installation
#### Installation steps:

1. Node JS and Yarn or NPM
   - Your computer must have Node.js and yarn/npm installed, to run this application.
  You can download Node.js from [NodeJS](https://nodejs.org) and yarn from [Yarn](https://yarnpkg.com/lang/en/docs/install/) or npm from [NPM](https://npm).

2. Make sure you have MongoDB running on your computer.
#### Development server
3. Clone this repository
#### Running the App
4. Open command line in the cloned folder,
   - To install dependencies, run ``` yarn ``` or ``` npm install ```
   - To run the application, run ```yarn dev ``` or ``` npm run dev ```
5. Open [localhost:3000](http://localhost:3000/) in the browser

#### Deployment
You can deploy the application on any server. You can make use of Netlify for client,a git-based workflow and powerful serverless platform to build, deploy, and collaborate on web apps or Heroku for full-stack web apps. Visit [Netlify](https://www.netlify.com/) or [Heroku](https://www.heroku.com/)

### Authors
#### Festus Ebin
* [GitHub](https://github.com/festusebin)
* [Linkedln](https://linkedin.com/in/festusebin)

`MERN Expense App` is a minimal expense tracking app

### Technology used

I made use of these `technology` during development.
* [React](https://reactjs.org/docs/getting-started.html)
* [Material UI](https://mui.com/)
* [NodeJS](https://nodejs.org)
* [Express Framework](https://expressjs.com)
* [MongoDB](https://mongodb.com)
<!--* [Redux]
* [Webpack] -->

<!--
----


----
## Get the book
#### [Full-Stack React Projects - Second Edition](https://www.packtpub.com/web-development/full-stack-react-projects-second-edition)
*Learn MERN stack development by building modern web apps using MongoDB, Express, React, and Node.js*

<a href="https://www.packtpub.com/web-development/full-stack-react-projects-second-edition"><img src="https://mernbook.s3.amazonaws.com/git+/Book_2Ed.jpg" align="center" width="400" alt="Full-Stack React Projects"></a> -->
#### More Details

----
<p>React combined with industry-tested, server-side technologies, such as Node, Express, and MongoDB, enables you to develop and deploy robust real-world full-stack web apps.</p>

<!--This updated second edition focuses on the latest versions and conventions of the technologies in this stack, along with their new features such as Hooks in React and async/await in JavaScript. The book also explores advanced topics such as implementing real-time bidding, a web-based classroom app, and data visualization in an expense tracking app. -->

<!-- Full-Stack React Projects will take you through the process of preparing the development environment for MERN stack-based web development, creating a basic skeleton app, and extending it to build six different web apps. You'll build apps for social media, classrooms, media streaming, online marketplaces with real-time bidding, and web-based games with virtual reality features. Throughout the book, you'll learn how MERN stack web development works, extend its capabilities for complex features, and gain actionable insights into creating MERN-based apps, along with exploring industry best practices to meet the ever-increasing demands of the real world.

Things you'll learn in this book:

- Extend a MERN-based application to build a variety of applications
- Add real-time communication capabilities with Socket.IO
- Implement data visualization features for React applications using Victory
- Develop media streaming applications using MongoDB GridFS
- Improve SEO for your MERN apps by implementing server-side rendering with data
- Implement user authentication and authorization using JSON web tokens
- Set up and use React 360 to develop user interfaces with VR capabilities
- Make your MERN stack applications reliable and scalable with industry best practices

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1839215410) today!

-->