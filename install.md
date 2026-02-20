** Install django Windows***

CHECK PYTHON VERSION
"python --version"


CREATE VIRTUAL ENVIRONMENT
"venv\Scripts\activate"


ACTIVATED  VENV
"venv/scripts/activate"

INSTALL DJANGO
"pip install django"

CHECK INSTALLATION
"django-admin --version"

CREATE PROJECT
'django-admin startproject usermanagement'

ENTER TO PROJECT FOLDER
'cd usermanagement'

RUN SERVER
"python manage.py runserver"


📌 settings.py
The heart of your Django project

Contains things like:

Installed apps

Database settings

Allowed hosts

Middleware

Static files settings

📌 urls.py
Controls the URL routing at the project level
You'll use it to connect app-specific routes

📌 wsgi.py & asgi.py
These are entry points for deploying Django on different servers
WSGI = traditional sync servers (like Gunicorn)
ASGI = supports async (e.g., WebSockets, Django Channels)

__init__.py
Makes this folder a Python module

📌 manage.py
- The command-line tool for:
- Running the server
- Applying migrations
- Creating apps
- Testing
- and more...