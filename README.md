User Authentication(Login, Register, Logout) Python-Django 

Guest visiting a site will be able to register and make their own username and password.
Users will be able to edit their information(username,password)


## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/rushi-jagdale/Login_Logout_Session.git
$ cd Login_Logout_Session
```

Create a virtual environment to install dependencies in and activate it:

```sh

$ Python3 -m venv env
$ source env/bin/activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up .

Once `pip` has finished downloading the dependencies:
```sh
(env)$ python3 manage.py migrate
(env)$ python3 manage.py makemigrations
(env)$ python3 manage.py runserver
```




