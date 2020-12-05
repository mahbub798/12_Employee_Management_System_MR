# Title of the project: Employee_Management_System


  [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/mahbub798/12_Employee_Management_System_MR)

  
## Description:
  
  Developers are often tasked with creating interfaces that make it easy for non-developers to view and interact with information stored in databases. Often these interfaces are known as **C**ontent **M**anagement **S**ystems. This project is to architect and build a solution for managing a company's employees using node, inquirer, and MySQL.
  
## Instructions

Designed the following database schema containing three tables:

![Database Schema](Assets/schema.png)

* **department**:

  * **id** - INT PRIMARY KEY
  * **name** - VARCHAR(30) to hold department name

* **role**:

  * **id** - INT PRIMARY KEY
  * **title** -  VARCHAR(30) to hold role title
  * **salary** -  DECIMAL to hold role salary
  * **department_id** -  INT to hold reference to department role belongs to

* **employee**:

  * **id** - INT PRIMARY KEY
  * **first_name** - VARCHAR(30) to hold employee first name
  * **last_name** - VARCHAR(30) to hold employee last name
  * **role_id** - INT to hold reference to role employee has
  * **manager_id** - INT to hold reference to another employee that manages the employee being Created. This field may be null if the employee has no manager
    
  ## Installation
  
  Clone the repo to your local machine and the following necessary dependencies must be installed to run the application properly: npm install inquirer mysql console.table
  
  ## Usage 
  
  Allows business owners to view and manage their employee structure.
  
  ## License
  
  This project is license under the MIT License license.
  
  ## Contributors
  1 Contributors
  
  ## Tests
  
  To run tests, you need to run the following command: node app.js

  # Questions

  If you have any questions about the repo, open an issue or contact mahbub798 directly mahbub798@gmail.com.


