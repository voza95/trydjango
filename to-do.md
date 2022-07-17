# To-Do list for trydjango

* Create a virtual env
    - Install virtualenv using pip
    - Run this cmd: "virtualenv ."
    - Activte it using "source bin/activate" on mac/linux.
* Install django
    - Run this cmd: "pip install django==2.0.7"
    - To save all the requirments used run "pip freeze > requirments.txt"
* Create simple project for now
    - Made a code directory "mkdir src" and move into "src" folder.
    - Create a blank django project "django-admin startproject trydjango ."
    - Start the server to check "python manage.py runserver"
* Create app modules
* Learn about Admin portal
    - Run the cmd: "python manage.py migrate"
    - To create new user run cmd: "python manage.py createsuperuser" and enter details (user:'vaibhav' and password:'Qwert@123')
* Learn templates
* Add DB support
* Work with API


> Note: Got error on updating spuer user on admin portal solution is to mirgrate/update.
Run the following CMD:
- python manage.py migrate
- python manage.py makemigrations
- python manage.py migrate