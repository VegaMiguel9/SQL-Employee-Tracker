# SQL-Employee-Tracker

his is a command-line application that allows you to view, add, and update employee-related information stored in a MySQL database. It was built using Node.js, the console.table library to format tables in the console, the dotenv library to load environment variables from a .env file, the inquirer library to prompt the user for input, and the mysql2 library to interact with the MySQL database.

## Getting Started
To use this application, you'll need to have Node.js and MySQL installed on your system. You'll also need to clone this repository and run npm install to install the necessary dependencies.
Next, create a .env file in the root directory of the project and add the following environment variables: PASSWORD='your_mysql_password'

Make sure to replace your_mysql_password with your actual MySQL password.

## Using Application
Now you want to go into the database folder and run the 'mysql -u root -p' command to go into mysql. Once in you need to create the database and populate the database.
Now that the databases are created and populated you can now cd back to the root folder and run npm start

This will start the inquirer prompt and allow you to select from a list of actions:

View all employees
View employees by department
View employees by manager
Add employee
Update employee role
Update employee manager
View all roles
Add role
View all departments
Add department
Quit

Selecting an action will either display information or prompt you for input to perform the desired operation.

## License
This project is licensed under the MIT License
