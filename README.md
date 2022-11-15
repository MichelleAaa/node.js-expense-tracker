# Expense Tracker

A web-based application featuring an expense tracker. Built with React, JSX, Node.js, Express, MongoDB, Mongoose, Axios, JavaScript, Bootstrap, Reactstrap, and CSS. create-react-app was used to set up the front-end.

## Project Screen Shots


Expense Tracker Start Screen

![Expense Tracker Start Screen](src/assets/readme-img/expense-tracker-intro.jpeg "To start, please enter a transaction in the Transaction Entry section.")

To start, please enter a transaction in the Transaction Entry section.


Positive Total Updates Balance Figure to Green

![Positive Total Updates Balance Figure to Green](src/assets/readme-img/expense-tracker-income.jpeg "After adding an income transaction, it will populate in the Income column of the Transaction History. Note that the Transaction detail section at the top will update the total for the Income column as well as the balance. Because the balance is positive, the total dollar amount value has turned green. Also, please note that each transaction can be either updated (with the green pencil icon) or deleted (with the red trashcan icon).")

After adding an income transaction, it will populate in the Income column of the Transaction History. Note that the Transaction detail section at the top will update the total for the Income column as well as the balance. Because the balance is positive, the total dollar amount value has turned green. Also, please note that each transaction can be either updated (with the green pencil icon) or deleted (with the red trashcan icon).



Zero Totals Will Reflect a Darker Color

![Zero Totals Will Reflect a Darker Color](src/assets/readme-img/expense-tracker-expense.jpeg "If the income and expense transactions even out to zero, the Balance field will reflect a darker color.")

If the income and expense transactions even out to zero, the Balance (aka total) field will reflect a darker color.


An Excess of Expense Transactions Will Reflect a Red Color for the Balance

![An Excess of Expense Transactions Will Reflect a Red Color for the Balance](src/assets/readme-img/expense-tracker-red.jpeg "When the total balance is a negative number, the Balance field will turn red.")

When the total balance is a negative number, the Balance field will turn red.


Making Updates Is Easy

![Making Updates Is Easy](src/assets/readme-img/expense-tracker-update-1.jpeg "Clicking on the green pencil icon will open a menu under the transaction item where updates can be made.")

Clicking on the green pencil icon will open a menu under the transaction item where updates can be made.


Update Completed

![Update Completed](src/assets/readme-img/expense-tracker-updated.jpeg "After filling out the fields and clicking submit, the update will reflect onscreen.")

After filling out the fields and clicking submit, the update will reflect onscreen. 


Delete All

![Delete All](src/assets/readme-img/expense-tracker-delete-all.jpeg "By clicking the Delete All button under Transaction History, all entries will be deleted.")

By clicking the Delete All button under Transaction History, all entries will be deleted.


Responsive Design

![Responsive Design](src/assets/readme-img/expense-tracker-responsive.jpeg "The application has been designed to respond to the window size to maintain functionality when used on a smaller screen.")

The application has been designed to respond to the window size to maintain functionality when used on a smaller screen.

## Launch Instructions

Clone this repository to your local machine. 

Navigate to the main project folder in the terminal and install the main packages for the front-end with the following command:

`npm install`

Next, please navigate to the backend folder and install the main packages for the back-end with the following command:

`npm install`

Next, you need to set up MongoDB locally. Please visit [here](https://www.prisma.io/dataguide/mongodb/setting-up-a-local-mongodb-database) for instructions.

Once MongoDB is set up, please ensure it's running in a separate terminal session.

Now that all required installations are in place, to start the front-end, please open the main folder in the terminal and use the following command:

`npm start`

Please leave the above terminal open. After loading, the React application should launch in your web browser. Assuming you have no other applications running, the application should launch at:

[http://localhost:3000](http://localhost:3000)


The above command only launches the front-end. To start up the backend, please open a separate terminal, navigate to the backend folder, and run the following command:

`nodemon server`

The second terminal will also need to be left open and running while you are using the application.

**Please note that this application requires an internet connection.  

## Reflection

I built this project after studying in the course focused on Node.js, Express, MongoDB, and Mongoose in NuCamp's Full Stack Web and Mobile Application Development Bootcamp. One of the challenges of this project included learning how to connect the backend to the frontend.

## References

- CodingTheSmartWay - "The MERN Stack Tutorial - Building a React CRUD Application from Start to Finish with MongoDB, Express, React, and Node.js" - https://codingthesmartway.com/the-mern-stack-tutorial-building-a-react-crud-application-from-start-to-finish-part-1/ (Inspiration for the initial setup of the frontend and the backend server.)
- Code With Sandip - "JavaScript Beginner Course | Practical JavaScript | Expense Tracker Application using JavaScript" - ht tps://www.youtube.com/watch?v=hAEL5beIbuw  (Inspiration for the project idea itself and some UI Design elements.)
- John Smilga - React Tutorial and Projects Course - Grocery Bud Mini Project - https://www.udemy.com/course/react-tutorial-and-projects-course/ (For additional inspiration regarding the React CRUD functionality.)

--------------------

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

--------------------