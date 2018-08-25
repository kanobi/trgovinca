===============================
trgovinca
===============================

.. image:: https://badge.fury.io/py/trgovinca.png
    :target: http://badge.fury.io/py/trgovinca

.. image:: https://pypip.in/d/trgovinca/badge.png
    :target: https://crate.io/packages/trgovinca?version=latest


nova trgovinca

* Free software: BSD license

Requirements
------------

* Django 1.10+
* Python 2.7
* Django CMS 3.4+

.. _django-cms: https://github.com/divio/django-cms

Installation
----------------------------

#. Clone the git repository.
#. Create a production.py file in trgovinca/trgovinca/trgovinca/settings by copying what's in the example_production.py
    * Fill database details in the file you just created
    * Add the site admins in the ADMINS variable
    * Add server host in ALLOWED_HOSTS

#. Install all third party packages by running::

    $ pip install -r requirements/development.txt

#. Apply migrations::

    $ python manage.py migrate

