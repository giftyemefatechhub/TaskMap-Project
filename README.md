# Task Management App

This is a task management web-based application built with HTML, CSS, JavaScript, SQLite, and Node.js. The app allows employees to track their progress for every sprint, document their mood, receive notifications for breaks, and includes a calendar feature.

## Features

- User Registration: Employees can create an account to access the app.
- User Login: Employees can log in to their accounts.
- Task Management: Employers can add tasks for employees to complete.
- Progress Tracking: Employees can track their progress for each sprint.
- Mood Tracking: Employees can document their mood.
- Break Notifications: Employees receive notifications for taking breaks.
- Calendar: The app includes a calendar feature for scheduling tasks and events.

## Usage
To access the Task Management app
- Register an account 
- log into your account
- Manage tasks
- Track your progress for each sprint 
- Document your mood
- Receive notifications for taking breaks
- Schedule tasks and events using calendar feature 

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/task-management-app.git
2. Install dependecies:
   cd task-management-app
   npm install
3. Set up the database:
   Modify the database configuration in database/db.js.

  Run the database migrations to create necessary tables:
  npx knex migrate:latest
4. Start the server:
   npm start

# File Structure
- app.js
- package.json
- views/
  - index.html
  - tasks.html
  - employee.html
  - mood.html
  - login.html
  - register.html
  - calendar.html
- public/
  - css/
    - style.css
  - js/
    - main.js
    - calendar.js
- controllers/
  - tasksController.js
  - employeeController.js
  - moodController.js
  - authController.js
  - calendarController.js
- models/
  - taskModel.js
  - employeeModel.js
  - moodModel.js
- database/
  - db.js
  - migrations/
    - create_tasks_table.js
    - create_employees_table.js
- routes/
  - index.js
  - tasks.js
  - employee.js
  - mood.js
  - auth.js
  - calendar.js
- middleware/
  - authMiddleware.js
- tests/
  - controllers/
    - tasksController.test.js
    - employeeController.test.js
    - moodController.test.js
    - authController.test.js
    - calendarController.test.js
  - models/
    - taskModel.test.js
    - employeeModel.test.js
    - moodModel.test.js
  - middleware/
    - authMiddleware.test.js
- README.md

## Troubleshooting
If you encounter any issues while using this application, please refer to the following resources;
-The documentation in this README file.
-The code comments and inline documentation  to understand the code and how it works.

# Contributing
Contributions are welcome! If you would like to contribute to the project, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Commit your changes and push the branch to your fork.
Submit a pull request to the main repository.
Please ensure that your code adheres to the project's coding conventions and includes appropriate tests.

# License
This project is licensed under the MIT License.
