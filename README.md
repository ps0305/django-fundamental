### Quick install guide
Before you can use Django, you’ll need to get it installed. We have a complete installation guide that covers all the possibilities; this guide will guide you to a simple, minimal installation that’ll work while you walk through the introduction.

### Install Python
Being a Python Web framework, Django requires Python. See [What Python version can I use with Django](https://docs.djangoproject.com/en/2.0/faq/install/#faq-python-version-support)? for details. Python includes a lightweight database called [SQLite](https://sqlite.org/) so you won’t need to set up a database just yet.

Get the latest version of Python at [Python Download](https://www.python.org/downloads/) or with your operating system’s package manager.

You can verify that Python is installed by typing `python` from your shell; you should see something like:
```js
Python 3.4.x
[GCC 4.x] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>>
```
### Set up a database
This step is only necessary if you’d like to work with a “large” database engine like PostgreSQL, MySQL, or Oracle. To install such a database, consult the database installation information.

### Remove any old versions of Django
If you are upgrading your installation of Django from a previous version, you will need to [uninstall the old Django version before installing the new version](https://docs.djangoproject.com/en/2.0/topics/install/#removing-old-versions-of-django).

### Install Django
You’ve got three easy options to install Django:

* [Install an official release](https://docs.djangoproject.com/en/2.0/topics/install/#installing-official-release). This is the best approach for most users.
* Install a version of Django [provided by your operating system distribution](https://docs.djangoproject.com/en/2.0/topics/install/#installing-distribution-package).
* [Install the latest development version](https://docs.djangoproject.com/en/2.0/topics/install/#installing-development-version). This option is for enthusiasts who want the latest-and-greatest features and aren’t afraid of running brand new code. You might encounter new bugs in the development version, but reporting them helps the development of Django. Also, releases of third-party packages are less likely to be compatible with the development version than with the latest stable release.

### Verifying
To verify that Django can be seen by Python, type python from your shell. Then at the Python prompt, try to import Django:
```js
>>> import django
>>> print(django.get_version())
2.0
```
