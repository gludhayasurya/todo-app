# todo-app

This project is a Todo list application built using the Laravel PHP framework. It allows users to manage their tasks efficiently by providing features such as creating, reading, updating, and deleting Todos.

**Table of Contents**

- Features
- Modules Used
- Getting Started
  - Prerequisites
  - Installation
- Usage

**Features**

- CRUD operations for Todo items (Create, Read, Update, Delete)
- Database persistence using MySQL
- User-friendly interface with Blade templates

**Modules Used**

The following modules/packages were used in this project:

- **Laravel Framework**: Provides the foundation for the application, including routing, ORM, and authentication.
- **Blade Templating Engine**: Allows for the creation of dynamic views using Laravel's Blade syntax.
- **MySQL Database**: Used for storing Todo items and their details.
- **Logging**: Used for log the datas like checking incoming requests and actions and passed parameters.
- **Mail**: Sending mails for every new task created.
- **Model**: Interact with our database and tables.
- **Migrations**: Used for maintaining versions.
- **Carbon**: Access the date and time.
- **Validator**: Validates the input requests.
- **Blade Directives**: Used for including the same blade file to many files by extending the layouts.
- **Components**: We can render the specific component blade files to all.
- **FrontEnd**: Html,Css,Bootstrap,Javascript,Jquery,Blade.

**Getting Started** 
**Prerequisites**

 PHP - 8.1 >
 MySQL
 Apache server (Any server to run the application) (LAMPP)
 Composer

 Downloading LAMPP will be easy for the Application deploy, since it includes Php,mysql,apache.

 **Installation**
  
  Clone the repository - 
  git clone  https://github.com/gludhayasurya/todo-app.git
 

 **Setup**

 Place the application in htdocs folder for local environment.
 Change the .env file as per your database config, like username,password,database,host.
 Then, open the application using like, localhost/ToDoApp/public

 **Usage**

 We can create todo tasks with status and with allocate department. From the tasks list, can create, edit,update and delete it.
 Once the task is created, we can change the completed status using checkbox, if it is checked, status changed to Completed, if it is unchecked it changed to In Progess.
 During the status change, notification will appear for the 3 seconds, like status changed successfully.
