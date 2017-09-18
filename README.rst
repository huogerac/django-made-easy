Django-Made-Easy
================

WHY
---

* If you are beginner, the official Django documentation gives the sensation that it's hard to start
* Most tutorials start from Models and Django Admin
* We want something production ready running in minutes
* We want beauty pages rather than everything in the admin side
* Learn from examples
* Be guided what can we do next


Ready to start with Django?
---------------------------

First, get Cookiecutter installed:::

    $ pip install "cookiecutter>=1.4.0"


Create your new project::

    $ cookiecutter https://github.com/huogerac/cookiecutter-django-made-easy

Answer the prompts with your own desired. For example::

    project_name [My First Django Project]:
    project_slug [myfirstdjangoproject]:
    author_name [Roger Camargo]:
    email [you@example.com]: huogerac@gmail.com
    version [0.0.1]:


Enter the project and install the project dependencies::

    $ cd myfirstdjangoproject/


Create the default database (users, sessions etc..)::

    $ ./manage.py migrate


To take a look at your new DJango project:::

    $ ./manage.py runserver
    Go to http://localhost:8000
    Check what you can do next...

.. class:: no-web

    .. image:: https://raw.githubusercontent.com/huogerac/django-made-easy/master/screenshots/django-mande-easy-guide.png
        :alt: guide
        :width: 100%
        :align: center


.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _Cookiecutter-django: https://github.com/pydanny/cookiecutter-django
.. _Virtualenv: https://virtualenv.pypa.io/en/stable/
