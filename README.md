[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/545oUMxH)

### Please use the following template to add a ReadMe for your repo.

## 1. Project Title and Description
    - Title: Student Management System: Blackboard
    - Description: Teachers can manage the students' information
## 2. Installation
    - Dependencies:
       -PostgreSqL
       -django == 5.0.3
       -django_environ == 0.11.2
       -psycopg == 3.1.18
       -psycopg2 == 2.9.9
       -sqlparse == 0.4.4
       -asgiref == 3.7.2
       -pip == 24.0
       -setuptools == 65.5.0
       -typing_extensions == 4.10.0
       

## 3. Usage
    - Examples: Include examples or code snippets to demonstrate how to use your project.
        1. get Django development server ready
        2. go to url example: http://127.0.0.1:8000/
        3. Homepage is view all student page. The page contains:
        - Add student http://127.0.0.1:8000/add/ or nav link
        - Edit student http://127.0.0.1:8000/edit/1/ or button of each student
        - delete a student button
        - more info button
        - log out button will go to login page
        - login goes to the main homepage
        
        
    
    - Configuration: Explain any configuration options or settings users might need to know about.
        - enable to change db information from .env
        
    
## 4. Features
    - List of Features: Outline the main features and functionalities of your project.
        - login, logout, and create account
        - view all students
        - add student
        - edit and delete each student
        
## 5. Contributing
    - Guidelines: Explain how others can contribute to your project, including information on submitting bug reports, feature requests, or code contributions.
        - users can report bugs, feature requests, or code contribution through github or email to us
        
    - Code Style: If applicable, provide guidelines or references to your code style.
        - https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/
        - bootswatch
## 6. Credits
    - Authors: Seongjun Kim, Aidel Royart.
    - Acknowledgments: 
        - How to Start Django Project with a Database(PostgreSQL): https://stackpython.medium.com/how-to-start-django-project-with-a-database-postgresql-aaa1d74659d8
        - How to use PostgreSQL with Django: https://www.enterprisedb.com/postgres-tutorials/how-use-postgresql-django
        - Django Login, Logout, Signup, Password Change, and Password Reset: https://learndjango.com/tutorials/django-login-and-logout-tutorial
        - bootswatch: https://bootswatch.com/
        - Font Awesome: https://fontawesome.com/
    
## 7. License
    - License Information: Specify the license under which your project is distributed.
        -django
        -PostgreSQL
        -bootstrap
        -fontawesome
## 8. Additional Sections (Optional)
    - FAQ: Include frequently asked questions and their answers.
    - Troubleshooting: Provide solutions to common issues or troubleshooting tips.
    - Roadmap: Outline the future development plans for your project.
    - Changelog: Document changes and updates to your project over time.

## Markdown Formatting Tips
  - Use headings (#, ##, ###, etc.) to structure your document.
  - Utilize lists (- or 1.) for easy-to-read information.
  - Include links to relevant resources or documentation.
  - Add code blocks using triple backticks (```) for code snippets.
  - Use images or diagrams to enhance understanding where applicable.
