# Forum
A simple forum that stores messages using PostgreSQL

This code is for a simple blog/forum that stores messages in a PostgreSQL database. Currently, this only supports adding messages however I will soon be adding the ability to delete, modify and comment messages. This project currently purely uses Python classes and I will most likely soon be porting it over to Flask and SQLAlchemy for ease of development. When this happens I'll just create a new repository as this one will then no longer be active.

In order to get this code up and running, it is expected that you are familiar with Python. Please see https://www.python.org/ for more information on installing and setting up python by yourself. Furthermore, it is advised to install vagrant on your own machine to get all additional programs quickly intsalled. Please see this link for more details on this process: https://www.udacity.com/wiki/ud197/install-vagrant.

## Instructions

1. Open up terminal/Git Bash and cd to you vagrant folder.

2. Type `vagrant up` and, after the virtual machine is turned on, type `vagrant ssh` to login

3. Type `cd /vagrant` to go to common directory and then cd into your forum folder.

4. Now type `python forum.py` and hit enter.

5. The server should be running locally at 'localhost:8000' and yo can view it yourself by typing 'localhost:8000' in your browser url bar.

6. You can now add your own forum posts. This input is sanitized by bleach so it is safe from cross site attacks and SQL injection. 
