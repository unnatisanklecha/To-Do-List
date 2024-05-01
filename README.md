# To-Do-List
This web application facilitates task management, allowing users to create, edit, view, update, and delete tasks. Additionally, it includes authentication functionality for user registration, login, and logout.

## Workflow
### Setup Instructions
1. Install Python and Django on your system if not already installed.
2. Create a new Django project: django-admin startproject todo_project.
3. Create a new Django app within the project: python manage.py startapp todo_app.
4. Define models, views, URLs, and templates within the Django app.
5. Run migrations to create the necessary database tables: python manage.py migrate.
6. Start the development server: python manage.py runserver.
7. Access the application through the provided local address.

## Database Design
The application utilizes Django's ORM to manage the database. The primary model used is the Task model, representing individual tasks in the to-do list. The database schema includes fields for task title, description, creation date, due date, and completion status.

## Frontend Implementation
The frontend of the application is built using HTML for structure and Django's templating engine for dynamic content rendering. CSS is utilized for styling to enhance the user interface.

## User Authentication
* Registration: Users can register for a new account by providing a username, email, and password through the registration form.
* Login: Registered users can log in to their accounts using their credentials through the login form.
* Logout: Users can log out of their accounts to end their session securely.

## Task Operations
* Create Task: Users can create new tasks by providing a title, description, and due date through the designated form.
* View Task: Tasks are displayed in a list format, showing their title, description, due date, and completion status. Users can click on a task to view its details.
* Edit Task: Users can edit existing tasks by accessing the edit form linked from the task details page. They can modify the title, description, due date, and completion status.
* Update Task: After editing, users can update the task by submitting the form, which saves the changes to the database.
* Delete Task: Users can delete tasks by clicking on the delete button associated with each task. A confirmation prompt ensures the task is deleted securely.

## Styling
CSS is applied to enhance the visual appeal and usability of the application. Styles are implemented to improve layout, typography, color scheme, and overall aesthetics.

## Future Development
Enhance the user interface with more interactive features using JavaScript to improve user experience.
Add functionality for task prioritization, categorization, and sorting to better organize tasks.
