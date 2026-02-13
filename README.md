## Simple API REST Program

A simple PHP API for managing a To-Do list, created while learning PHP backend development. Supports CRUD operations for tasks.

### About

This project is a basic PHP API for managing a To-Do list, developed while learning PHP backend development. It provides endpoints to list, create, update, and delete tasks, using a MySQL database to store task data. The project allowed practice with RESTful API concepts, handling HTTP requests, and interacting with a database through PHP, making it a practical introduction to backend development.

### Endpoints
- **GET /index.php**: List all tasks or get a specific task by ID (`?id=1`).
- **POST /index.php**: Create a new task. Requires JSON body: `{ "title": "Task title" }`.
- **PUT /index.php?id=1**: Update a task. Requires JSON body: `{ "title": "Updated title" }`.
- **DELETE /index.php?id=1**: Delete a task by ID.

<br>
<p align="center" style="opacity:0.6;">
MIT License – see the <a href="LICENSE">LICENSE</a> file for details.
</p>
