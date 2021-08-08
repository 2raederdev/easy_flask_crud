# Book Manager

This app has been developed following the tutorial 'Building a CRUD application with Flask and SQLAlchemy' by Gareth Dwyer.

`https://www.codementor.io/@garethdwyer/building-a-crud-application-with-flask-and-sqlalchemy-dm3wv7yu2`

## SQLite

SQLite is a file-based database and comes bundled with the standard installation of Python. Thus, we can store the data in a file on our file system, without needing to install a huge Relational Database Management System (RDBMS).

## Getting started

You can install the required libraries through pip by running the following command:

pip3 install flask sqlalchemy flask-sqlalchemy

To start the app, run python3 bookmanager.py in the console from the app root directory.

## Initializing the database

Run the following commands in a Python shell in the project directory in order to create the database and create the book table where the books will be stored.

$ from bookmanager import db
$ db.create_all()
$ exit()
