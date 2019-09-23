# wordpress-django-plugin
A wordpress plugin to manage an associated Django environment

This project aims to provide an environment for a Django project to integrate with a Wordpress site. At this stage this is expected to be impleented as follows:
* A wordpress plugin that 1/ tests that a python environment is available, 2/ Configures .htaccess for a url path prefix to be forwarded to a (eg) python/gunicorn environment. The url path prefix to be specified in the wordpress admin panel
* A django app that provides a set of legacy models that represent the Wordpress database schema
* Ability for the Django project to create custom Wordpress tables
* Ability for the Django project to connect to a 2nd database where the project will be responsible for database migrations 
