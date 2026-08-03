Heading: "API Design"
Purpose: Defines the RESTful API endpoints for WIP Studio services.
Endpoints:
User API:
GET /users: Returns a list of all users.
POST /users: Creates a new user with name, email, and role.
GET /users/{id}: Returns details of a specific user.
Project API:
GET /projects: Returns all projects.
POST /projects: Creates a new project with title and owner.
GET /projects/{id}: Returns details of a specific project.
Task API:
GET /tasks: Returns all tasks.
POST /tasks: Creates a new task linked to a project.
GET /tasks/{id}: Returns details of a specific task.
Authentication: Use API keys in headers for all protected routes.
Data Format: All requests and responses are in JSON.