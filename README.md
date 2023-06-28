# Romeo's Adventure

Romeo's Adventure description would go here. We should detail out things here..

## Installation & Configuration

This repo contains two applications - the backend application, which is a django web server app, and the frontend application, which a react.js app.

### General setup
1. Clone the repo

### Setup & Configure the backend
You must have postgres installed.

1. Navigate to the `backend` directory 
2. Create a python virtual environment: `python -m venv .venv`
3. Activate python virtual environment: `source .venv/bin/activate
4. Install python dependencies: `pip install -r requirements.txt`
5. Create the postgres db the app will use:
	a. Make sure the "postgres" postgres user exists.
	b. Create a database named "romeo"
        'NAME': 'romeo',
        'USER': 'postgres',
        'PASSWORD': '123'
6. Run the database migrations to create the data schema: `python manage.py migrate`

## Running the application

### Backend
In the `backend/` directory, run `python manage.py runserver

## Project setup
* Clone the repo
* Set up your **venv** (Should look like this when done): `romeo\backend\venv`
  * If you want to test your Django project to ensure it was setup correctly, now would be a good time before continuing.
* Set up your npm modules (Should look like this when done): `romeo\frontend\node_modules`
  * Testing Vite project just like with Django can be done at this time
* Run the watch command, run the Django server, go to 127.0.0.1:8000 and see something like this...
  * https://gyazo.com/0a21f586e999fafb8c7a5d206ac68cdf

#


