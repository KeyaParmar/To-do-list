# To-Do List Web App

## Project Overview

The To-Do List Web App is a simple yet efficient task management application that helps users keep track of their daily activities. Users can add tasks, mark them as completed, and delete them when done. The interface is clean and intuitive, allowing users to manage their to-dos with ease and stay organized.

## Project Files Description

1. **solution.js** – Handles all client-side logic, including adding tasks, marking them as done, and removing them from the list.
2. **index.ejs** – The main template file that renders the to-do list interface and task form.
3. **header.ejs** – EJS partial used for rendering the top navigation bar or header elements.
4. **footer.ejs** – EJS partial used to render footer content across all pages.
5. **style** – Folder containing the main CSS styles that define the layout, colors, and overall look of the app.
6. **assets** – Folder for storing static files such as images, fonts, or icons used in the application.

## Features

- Add Tasks  
  Users can add new tasks with a simple form input, which gets stored in the backend.

- Mark Tasks as Done  
  Each task has a checkbox that allows users to mark it as completed.

- Delete Tasks  
  Users can easily remove any task they no longer need from their list.

- Persistent Task Storage  
  All tasks are stored in a PostgreSQL database, ensuring they are not lost between sessions.

## Technologies Used

- Node.js & Express.js – Backend runtime and framework used to build the server and handle API requests.
- EJS – Embedded JavaScript templating engine for dynamically generating HTML views.
- PostgreSQL – Relational database used for storing all tasks and their completion status.
- HTML & CSS – Used to structure and style the front-end of the application.
- JavaScript – Used on the frontend for interactive behavior like task actions.
- REST API – RESTful endpoints handle task creation, updates, and deletion between the frontend and backend.

## Dataset / User Input

- Users enter tasks manually through an input form.
- Tasks are stored with a completion status (checked or not).
- Data is persisted using PostgreSQL so tasks remain saved across browser sessions.
