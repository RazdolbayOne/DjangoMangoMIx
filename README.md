# DjangoMangoMIx
Django framework testing site 

link to tutorial - https://docs.djangoproject.com/en/3.1/intro/tutorial01/ 

#how to run server 
```   
$ python manage.py runserver
```  
The development server automatically reloads Python code for each request as needed. 
You don’t need to restart the server for code changes to take effect. However, some actions like adding 
files don’t trigger a restart, so you’ll have to restart the server in these cases.

We’ll cover them in more depth in a later part of the tutorial, but for now, 
remember the three-step guide to making model changes:

Change your models (in models.py).
Run python manage.py makemigrations to create migrations for those changes
Run python manage.py migrate to apply those changes to the database.