.. image:: http://i.imgur.com/BIcvhtP.jpg
   :width: 100%
   :alt: grappa logo
   :align: center


|Build Status| |PyPI| |Coverage Status| |Documentation Status| |Stability| |Quality| |Versions|

grappa-http
-----------

`grappa`_ plugin for HTTP assertions.

To get started, take a look to the `documentation`_ and `tutorial`_.

Features
--------

-  Full-featured HTTP response assertions.
-  Supports any protocol primitive assertions.
-  First-class support for JSON body assertion.
-  JSONSchema validation support.
-  Featured regular expression based assertion.
-  Works with ``requests``, ``aiohttp`` and ``urllib3``.
-  Friendly and detailed assertion error reporting.
-  Provides both ``expect`` and ``should`` assertion styles.
-  Testing framework agnostic. Works with ``unittest``, ``nosetests``, ``pytest``
-  Works with Python 2.6+, 3+ and PyPy.


Installation
------------

Using ``pip`` package manager:

.. code-block:: bash

    pip install --upgrade grappa-http

Or install the latest sources from Github:

.. code-block:: bash

    pip install -e git+git://github.com/grappa-python/http.git#egg=grappa


.. _Python: http://python.org
.. _`grappa`: https://grappa.readthedocs.io
.. _`documentation`: http://grappa-http.readthedocs.io
.. _`tutorial`: http://grappa-http.readthedocs.io/en/latest/tutorial.html

.. |Build Status| image:: https://travis-ci.org/grappa-python/grappa-http.svg?branch=master
   :target: https://travis-ci.org/grappa-python/grappa-http
.. |PyPI| image:: https://img.shields.io/pypi/v/grappa-http.svg?maxAge=2592000?style=flat-square
   :target: https://pypi.python.org/pypi/grappa-http
.. |Coverage Status| image:: https://coveralls.io/repos/github/grappa-python/http/badge.svg?branch=master
   :target: https://coveralls.io/github/grappa-python/http?branch=master
.. |Documentation Status| image:: https://readthedocs.org/projects/grappa-http/badge/?version=latest
   :target: http://grappa-http.readthedocs.io/en/latest/?badge=latest
.. |Quality| image:: https://codeclimate.com/github/grappa-python/http/badges/gpa.svg
   :target: https://codeclimate.com/github/grappa-python/http
   :alt: Code Climate
.. |Stability| image:: https://img.shields.io/pypi/status/grappa-http.svg
   :target: https://pypi.python.org/pypi/grappa-http
   :alt: Stability
.. |Versions| image:: https://img.shields.io/pypi/pyversions/grappa-http.svg
   :target: https://pypi.python.org/pypi/grappa-http
   :alt: Python Versions