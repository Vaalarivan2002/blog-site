# blog-site
I made this blog website as an educational Django project. This site enables users to view and create new blogs.

## Steps to run the site in your local machine
* Clone this repository into your local machine after installing Django.
* Generate a secret Django key and put it in .env file using the variable 'SECRET_KEY'.
* Run 'python manage.py makemigrations' followed by 'python manage.py migrate' in order to save the model schema in the database.
* Run 'python manage.py runserver' to start the Django server.