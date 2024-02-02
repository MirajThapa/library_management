enviroment for django
Firstly open the folder and from cmd line do the following:
* pip install virtualenv    -- This is to create a virtual room 
* virtualenv env
* activate the Scripts from virtual env folder
* pip install Django
* django-admin startproject Library_management  -- app is created
* python manage.py startapp library  -- creates an app library where we can build models, views

  Then we have to add library to INSTALLED_APPS in setting.py
To run the django app
* python manage.py runserver

For the model migration
* python manage.py makemigrations
* python manage.py migrate

For this project I'd used PostgreSQL database.
We have to specify database in setting.py to connect to our local server.

Here the views are function based. For all the features functions had been declared and endpoints are provided. Test cases has been written and all the API works properly. The data has been serilized into JSON format.
Moreover in future we can add proper UI using Templates and authentication could be done.
Proper documentation has been done.
