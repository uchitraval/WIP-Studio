Heading: "Entity Engine Design"
Purpose: Models core business entities for WIP Studio.
Entities:
User: user_id (unique identifier), name (string), email (string), role (string).
Project: project_id (unique identifier), title (string), owner_id (foreign key to User), start_date (date), status (string).
Task: task_id (unique identifier), project_id (foreign key to Project), description (string), due_date (date), status (string).