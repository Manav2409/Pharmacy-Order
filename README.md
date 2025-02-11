﻿# Flask-Pharmacy-OrderApp
A Flask application with SQL Alchemy as Object Relational Mapper(ORM)

The web page displays the names of the medicines you store in the database

## Utility
The user can input medicine names when new stock arrives

The user can delete medicine data when stock of a certain medicine gets over
 
## Installation
To run the app flawlessly, satisfy the requirements
```
$ pip install -r requirements.txt
```
### Set Environment Variables
```
$ export FLASK_APP=app.py
$ export FLASk_ENV=development
```
### Start Server
```
$ flask run
```
Or run this command
```
$ python -m flask run
```
### For Database
```
$ pip install flask-sqlalchemy
```
