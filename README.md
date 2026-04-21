Room booking system
=====
The web application is build with python Flask framwork along with SQLite3 database. It has basic login system since the booking have to be done with authentication. A admin account is created by default, with username: admin, and password: admin. The administrator have the access to directly manipulate team and users. 

GitHub Pages: https://pranav362k05.github.io/room-booking-system/

## Setup
1. Install flask and packages
```
$ pip install flask
$ pip install flask-wtf
$ pip install flask-sqlalchemy
$ pip install flask-migrate
$ pip install flask-login
```
2. Define the project
```
$ export FLASK_APP=lab2.py
```

3. Init the database
```
$ flask db init
```

## Migrating data
1. Run the migration command from the project directory to create tables
```
$ flask db upgrade
```
2. Populate the database with dummy data(if weren't populated after migration)
```
$ python populate.py
```

# Running
1. Run the flask application from the project directory, running on localhost
```
$ flask run
```
2. Open the app in browser: http://127.0.0.1:5000/ [localhost](http://127.0.0.1:5000/)
