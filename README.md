## Description

wwwrate is a web application that is like Awwards. Users are able to see landing page of projects that other users have uploaded. They also get to rate and review  other users projects and get the average of the results. Users also get to upload landing pages of their projects so that they can be reviewed and also rated. Users can also view their profile
## Features

The home page allows users to see various landing pages of projects:
User can see their profile
User can upload images

## View Live Site here

https://celawwards.herokuapp.com/

## Technologies Used

- Python 3.8
- Django MVC framework
- HTML, CSS and Bootstrap
- JavaScript
- Postgressql
- Heroku
## Prerequisite

The wwwrate project requires a prerequisite understanding of the following:

Django Framework
Python3.8
Postgres
Python virtualenv

## Setup and installation

# Clone the Repo from

https://github.com/chepceline/project-review.git

# Activate virtual environment

Activate virtual environment using python3.6 as default handler virtualenv -p /usr/bin/python3.8 venv && source venv/bin/activate

# Install dependancies

Install dependencies that will create an environment for the app to run pip3 install -r requirements.txt

# Create the Database

- psql
- CREATE DATABASE 'database-name';
# .env file

Create .env file and paste paste the following filling where appropriate:

SECRET_KEY = '<Secret_key>'
DBNAME = '<database_name>'
USER = '<Username>'
PASSWORD = '<password>'
DEBUG = True

# Run initial Migration

python3.8 manage.py makemigrations
python3.8 manage.py migrate

# Run the app

python3.8 manage.py runserver
Open terminal on localhost:8000


# Contributors
- Damaris Chepchirchir

# Contact Information
chepceline25@gmail.com