# Your first Django app !

This is the code for my video : https://youtu.be/fbUdzqtlfo8

## Step 1 - Make sure you have installed Python
You can download python from here : https://www.python.org/downloads/

## Step 2 - Installing Django
To install Django, open up your command prompt and type :
```
pip install django
```

## Step 3 - Create a new project
Create a new Django project by typing : 
```
django-admin startproject myfirstproject
```
Where `myfirstproject` is your project name. 

## Step 4 - Run your project !
To start the local server and run the project, type :
```
cd myfirstproject
python manage.py runserver
```
Now open your web browser and go to http://127.0.0.1:8000 to see your project in action!
To stop the server press Ctrl+c

## Step 5 - Make a new app 
A Django project can have any number of apps. To make a new app:
```
python manage.py startapp myapp
```
Where `myapp` is your app name. 

## Now you are ready to start writing Django code!
Watch the video https://youtu.be/fbUdzqtlfo8 to see how you can add a new URL and define a new view, to make your app display Hello World!