INTRODUCTION

This project is just simple project about personal blog website where user can log in,view profile,comment, post andd also create a post.

Template is written using Django and Phython3

USAGE

If your project is already in an existing python3 virtualenv first install django by running

$ pip install django

And then run the django-admin.py command to start the new project:


No Virtualenv

This assumes that python3 is linked to valid installation of python 3 and that pip is installed and pip3is valid for installing python 3 packages.

Installing inside virtualenv is recommended, however you can start your project without virtualenv too.

If you don't have django installed for python 3 then run:

$ pip3 install django

After that just install the local dependencies, run migrations, and start the server.

Getting Started

$ git clone git@github.com/USERNAME/{{ project_name }}.git
$ cd {{ project_name }}
$ python manage.py migrate
$ python manage.py runserver

