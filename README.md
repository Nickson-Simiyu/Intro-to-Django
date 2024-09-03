# Intro to Django

Welcome to the **Intro to Django** repository! This project serves as a starting point for learning Django, a high-level Python web framework that encourages rapid development and clean, pragmatic design.

## Table of Contents

- [Introduction](#introduction)
- [Project Setup](#project-setup)
- [Running the Project](#running-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)

## Introduction

This repository is my journey of learning Django, a popular Python web framework used for building scalable and secure web applications quickly. The goal is to build a simple web application to understand the core concepts of Django, such as:

- Setting up a Django project
- Creating and managing Django apps
- Working with models, views, templates, and URLs
- Utilizing the Django Admin interface
- Handling static files and media
- Creating forms and handling user input
- Understanding Django's ORM (Object-Relational Mapping)
- Implementing basic CRUD (Create, Read, Update, Delete) functionality

## Project Setup

To run this Django project on your local machine, follow the steps below:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/intro-to-django.git
   cd intro-to-django/mysite
2. Create a virtual environment:
   python -m venv venv

3. Activate the virtual environment:
   venv\Scripts\activate
   
4. Install the required dependencies:
   pip install -r requirements.txt

5. Apply database migrations:
   python manage.py migrate

6. Create a superuser (for accessing the Django admin):
   python manage.py createsuperuser

7. Run the development server:
   python manage.py runserver

8.Open your browser and go to 'http://127.0.0.1:8000/' to view the app.

Running the Project
Once the server is running, you can interact with the web application through your browser. Access the Django admin interface at 'http://127.0.0.1:8000/admin/' using the superuser credentials you created.Running the Project

Features
- Basic Django setup and configuration
- Custom models and migrations
- Basic views, templates, and URL routing
- User authentication and authorization
- Admin interface customization

Technologies Used
- Django: The primary web framework for Python.
- Python: Programming language used.
