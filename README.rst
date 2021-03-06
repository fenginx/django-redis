==============================
Redis cache backend for Django
==============================

Full featured redis cache backend for Django.

Documentation
-------------

Read the Docs: https://django-redis.readthedocs.org/en/latest/

Features:
---------

* In active development.
* Sharding supported in a single package.
* Complete battery of tests (accepting improvements).
* Used in production environments on several projects.
* Can set keys with infinite timeout: ``cache.set('key', 'value', timeout=0)``
* Pluggable clients.
* Python3 support with same codebase.
* Same behavior as memcached backend with connection exceptions.
* Supports Django: 1.3, 1.4 and 1.5
* You can take advantage of the connection pool to directly access to the connection object of redis.


Future plans/In developement
----------------------------

* Auto failover
* Master-Slave pluggable client.


How to install
--------------

Run ``python setup.py install`` to install,
or place ``redis_cache`` on your Python path.

You can also install it with: ``pip install django-redis``
