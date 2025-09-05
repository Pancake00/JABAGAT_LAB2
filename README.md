### Project Overview
- The project shows how to create all CRUD (Create, Read, Update, Delete) activities in the table. The purpose of this is to configure database and have a clear project structure which are routes, controllers, and configuration.

### Setup Steps
- Install xampp and ensure that MySQL is running and created a database.
- Install the required libraries and put the following files inside the folder.
- Put the port configuration.
- Check if the server is running.
- Check on postman if its also working.

### How to run & test
- Open Xampp
- Start Apache and MySQL
- Run the server
- Check on postman to run the test

### API endpoints
- Get /api/health to check the server connectivity
- Post /api/students to create new student
- Get /api/students to retrieve the students
- Get /api/students/:id to get a specific student by putting their id
- Put /api/students/:id to update
- Delete /api/students/:id to delete a student
