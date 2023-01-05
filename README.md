# RyChat

I've created a simple chatroom app using Django/Python/SQLite for the backend and JavaScript/Ajax for some frontend tools along with HTML and CSS. A user can create a room and exchange messages with other users in the same room. 

When starting a django project it is important to run the 
`django-admin startproject <name_of_project>` command.

You can then run `python3 manage.py startapp <name_of_app>` command and when ready to make migrations run `python3 manage.py makemigrations` and `python3 manage.py migrate`.

You will then need to create a superuser to access your SQLite database using the `python3 manage.py createsuperuser` command.

To run your django server simply use the `python3 manage.py runserver` command.
