### [Project Homepage][1]
### [API Documentation][2] and [Manual][3]

--------------------

About
=====

Adds an [SPF][4] authorization extension to python-slimta. This enables MTAs
built on `python-slimta` to apply policies to incoming mail based on the result
of an SPF lookup check.

[![Build Status](http://ci.slimta.org/job/python-slimta-spf/badge/icon)](http://ci.slimta.org/job/python-slimta-spf/)

Getting Started
===============

If you haven't yet installed [`python-slimta`][5], refer to the "Getting
Started" section. Once inside your virtualenv:

    (.venv)$ python setup.py develop

To run the suite of included unit tests:

    (.venv)$ nosetests

Refer to the [API Documentation][2] and [Manual][3] for more information on
using this extension.

[1]: http://slimta.org/
[2]: http://docs.slimta.org/en/latest/api/extra.spf.html
[3]: http://docs.slimta.org/en/latest/manual/extensions.html#enforce-spf
[4]: http://www.openspf.org/
[5]: /slimta/python-slimta

