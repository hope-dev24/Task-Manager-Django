# Task Manager (Django)

A full-stack task management web app built with Django. Users can create, view, mark as complete, and delete tasks through a browser interface — all data is stored in a real database.

## Features
- Add new tasks through a web form
- View all tasks and their completion status
- Toggle a task between "Done" and "Not Done"
- Delete tasks
- All data persists in a database (SQLite)
- Styled front-end with custom CSS

## Tech Used
- Python
- Django
- SQLite (default Django database)
- HTML / CSS

## How to Run
1. Install Django: `pip install django`
2. Run migrations: `python manage.py migrate`
3. Create an admin account (optional, for the Django admin panel): `python manage.py createsuperuser`
4. Start the server: `python manage.py runserver`
5. Visit `http://127.0.0.1:8000/` in your browser

## What I Learned
This project was my first hands-on build with Django, covering the full request/response cycle: models and migrations, the Django admin, URL routing (project-level and app-level), views, templates with Django's template language, handling GET and POST requests, and connecting static CSS files. I also debugged a real static file path issue during development.
