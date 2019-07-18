# DG assignment 

Write a simple Python Flask or Django app that responds to REST API requests and provides a simple endpoint named “/all-caps” and a cucumber test against it. Include a short readme on how to install the python environment after cloning the repo from github and how to start the app in one window and run it in another.

## Tools 

I am running this application on a macOS system.
For my text editor I used atom.

Django and Python must be installed in your system to access application.
**I also Installed Postgres to use as my DB server instead of db.sqlite3.**

## Installation of Postgres  

Go to [Postgres](https://www.postgresql.org/) to install  application.

Once installed open Postgres and click on the icon of the DB stack with Postgres underneath:
<img width="455" alt="Postgres DB" src="https://user-images.githubusercontent.com/15825446/61489711-85eb6400-a968-11e9-92e6-41ebaa9011b4.png">

Terminal should open and you should see this:

<img width="403" alt="Postgres create password" src="https://user-images.githubusercontent.com/15825446/61489713-88e65480-a968-11e9-8fdc-2fd30a2ec7b7.png">

once there it will prompt for you tocreate a password<br/>
Then you should create your database 
```SQL
CREATE DATABASE portfolio
```

## connecting Postgres with Django 
Once database is created head to setting.py in the portfolio folder<br/>
Then add the following code below and enter your own password that you created for your database.
<kbd>
<img width="512" alt="connect Postgres with Django" src="https://user-images.githubusercontent.com/15825446/61489618-5c323d00-a968-11e9-8234-7bff76d8bcee.png"> 
</kbd>
## Migrate if needed 

```bash
python3 manage.py makemigrations
```
```bash 
python3 manage.py migrate
```
# HelloWorld! REST Framework

run the portfolio-project on the Django server using localhost:8000<br\>
**HelloWorld** should show up onm the webpage.




