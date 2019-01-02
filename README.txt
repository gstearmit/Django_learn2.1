###---------------- Start ENV Project --------------------
    $ virtualenv -p python learn-django2.1
    $ source learn-django2.1/bin/activat
    $ pip  install -r requirements.txt


###-------------Create project-----------
    $ django-admin startproject mysite
    $ cd mysite
    $ python manage.py runserver 8991

###----------------Creating the Polls app 02/01/2018---------------------
    $ python manage.py startapp polls

    Page not found?
    If you get an error page here, check that you’re going to http://localhost:8991/polls/ and not http://localhost:8991/.


### ----------add git--------------
    …or create a new repository on the command line
    echo "# Django_learn2.1" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/gstearmit/Django_learn2.1.git
    git push -u origin master
    …or push an existing repository from the command line
    git remote add origin https://github.com/gstearmit/Django_learn2.1.git
    git push -u origin master