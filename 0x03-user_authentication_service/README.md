# 0x03-user_authentication_service

In the industry, you should not implement your own authentication system and use a module or framework that doing it for you (like in Python-Flask: Flask-User). Here, for the learning purpose, we will walk through each step of this mechanism to understand it by doing.

## Documentation

[HTTP Status code](https://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html)
[Request module](https://requests.kennethreitz.org/en/latest/user/quickstart/)
[Flask documentation](https://flask.palletsprojects.com/en/1.1.x/quickstart/)

## TASKS

[0. User model](https://github.com/Mmaureeny/alx-backend-user-data/blob/master/0x02-Session_authentication/models/user.py)
In this task you will create a SQLAlchemy model named User for a database table named users (by using the mapping declaration of SQLAlchemy).

The model will have the following attributes:
id, the integer primary key
email, a non-nullable string
hashed_password, a non-nullable string
session_id, a nullable string
reset_token, a nullable string

