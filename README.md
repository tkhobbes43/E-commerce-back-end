<h1 align="center"> E-Commerce Back End </h1>



## Description

I want to develop a back end for my e-commerce website.  To do that, this app will configure a working Express.js API to use and Object Relational Mapping package  called Sequelize to interact with a MySQL database so that you can view, add, edit, and delete data.

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Questions](#questions)

## User Story
```md
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business
```

## Acceptance Criteria
```md
GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database 
```

## Installation
This application will require you to use Node.js, Express.js, and the Sequelize ORM to connect to the database and interact with it. To run this app, you will need to `npm install` against my package.json file to get all the required npm packages.  Second, to connect to the database, you need to login to your MySQL by running `mysql -u root -p` on the command while in this app's directory and enter your password which should be entered in the .env file.  Once you are in MySQL, you will have to run the schema with `source db/schema.sql` on the command line.  Then you can use the script `npm run seed` to seed the database. Finally, connect to the server by running `npm run start`.

## Usage
This application will allow users to view, create, edit, and delete categories, products, and tags to the database.

![screenshot of MySql database in action](./assets/images/Screenshot%202022-07-07%20225250.png)

![screenshot of Insomnia testing application](./assets/images/Screenshot%202022-07-07%20230824.png)

View video walkthrough to see MySQL database in action [here](https://drive.google.com/file/d/1R5zX4sO303OBCqBj-VDgVyCidmDu_hax/view?usp=sharing).
View video walkthrough to see how the API routes for the HTTP requests are done for this app [here](https://drive.google.com/file/d/1UMfqk7LOmO10R1GE-Uu5klkDIXdmuV_A/view?usp=sharing).

## Questions
For any questions or concerns, contact me at either my [GitHub](https://github.com/tkhobbes43)
or my email: t.k.hobbes43@gmail.com
