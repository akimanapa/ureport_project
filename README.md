ureport-project
===============

new ureport based on the latest rapidsms 0.13.0 and github.com/nyaruka's httprouter

To setup
--------

    git clone https://github.com/srugano/ureport-project.git ureport_project
    cd ureport_project
    pip install -r requirements/base.txt
    pip install -r requirements/ibisabwa.txt
    git submodule update --init

Run syncdb:

    python manage.py syncdb
    python manage.py migrate

You should now be able to run the development server:

    python manage.py runserver

