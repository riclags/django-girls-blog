1st Django Girls Cagayan de Oro Workshop
========================================

I would like to congratulate **Barbie**, **Mary Grace** and **Shedee Grace** for having taken part and completed the very first Django Girls CDO workshop! It was an honor coaching this talented group of girls. I hope that as their coach I was able to guide them properly and that I have also met their expectations for the workshop.

Kudos also to the organizers of `Django Girls CDO <https://twitter.com/djangogirlscdo>`_ for a successful event; thanks for inviting me to be a coach.

How to Use This Repository
--------------------------

This repository contains the code I did when I followed along the Django Girls tutorial (https://tutorial.djangogirls.org/en/) during the workshop proper.

Clone the repository (and go inside it), create a virtual environment (and activate), install the Django package, migrate the models, create a superuser and run the local server.

::

    $ git clone https://github.com/riclags/django-girls-blog.git
    $ cd django-girls-blog
    django-girls-blog $ python3 -m venv myvenv
    django-girls-blog $ source myvenv/bin/activate
    (myvenv) django-girls-blog $ pip install Django~=1.10.0
    (myvenv) django-girls-blog $ python manage.py migrate
    (myvenv) django-girls-blog $ python manage.py createsuperuser
    (myvenv) django-girls-blog $ python manage.py runserver
    
The workshop proper was held on May 6, 2017 at the ICT Training and Internship Center (Cagayan de Oro), DICT MC2 Misamis Oriental Office, T. Chaves cor Tiano Brothers Sts., Cagayan de Oro from 8AM to 6PM.