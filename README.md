#DG assignment 

Write a simple Python Flask or Django app that responds to REST API requests and provides a simple endpoint named “/all-caps” and a cucumber test against it. Include a short readme on how to install the python environment after cloning the repo from github and how to start the app in one window and run it in another.

## Tools 

I am running this application on a macOS system.
For my text editor I used atom.

Django and Python must be installed in your system to access application. 
I also Installed Postgres to use as my DB server instead of db.sqlite3

## Installation of Postgres  

Go to [Postgres](https://www.postgresql.org/) to install  application.

Once installed open Postgres and click on the icon of the DB stack with Postgres underneath.

past image here 

create database 

## connecting Postgres with Django 

head to setting.py in the portfolio folder 

past image here 

## Migrate if needed 

```bash
python3 manage.py makemigrations
```
```bash 
python3 manage.py migrate
```
# HelloWorld! REST Framework
