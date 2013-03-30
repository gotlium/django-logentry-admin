=====================
django-logentry-admin
=====================

Add Django LogEntries the the Django admin site.

Allows to view all log entries in the admin.

Based on: `Django snippet 2484 <http://djangosnippets.org/snippets/2484/>`_


Installation
============

Install from source:

    git clone https://github.com/gotlium/django-logentry-admin.git
    cd django-logentry-admin
    python setup.py install

To add this application into your project, just add it to your
``INSTALLED_APPS`` setting::

    INSTALLED_APPS = (
        ...
        'logentry_admin',
    )
