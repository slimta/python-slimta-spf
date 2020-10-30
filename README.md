#### [Project Homepage][1]
#### [API Documentation][2] and [Manual][3]

--------------------

### NOTE: This library has been [moved](https://www.slimta.org/blog/2020-10-30.html) into [python-slimta](https://github.com/slimta/python-slimta).

About
=====

Adds an [SPF][4] authorization extension to python-slimta. This enables MTAs
built on `python-slimta` to apply policies to incoming mail based on the result
of an SPF lookup check.

[![Build Status](https://travis-ci.org/slimta/python-slimta-spf.svg?branch=master)](https://travis-ci.org/slimta/python-slimta-spf)
[![Coverage Status](https://coveralls.io/repos/github/slimta/python-slimta-spf/badge.svg?branch=master)](https://coveralls.io/github/slimta/python-slimta-spf?branch=master)

Getting Started
===============

If you haven't yet installed [`python-slimta`][5], refer to the "Getting
Started" section. Once inside your virtualenv:

    (.venv)$ python setup.py develop

To run the suite of included unit tests:

    (.venv)$ py.test

Refer to the [API Documentation][2] and [Manual][3] for more information on
using this extension.

[1]: http://slimta.org/
[2]: http://docs.slimta.org/latest/api/extra.spf.html
[3]: http://docs.slimta.org/latest/manual/extensions.html#enforce-spf
[4]: http://www.openspf.org/
[5]: https://github.com/slimta/python-slimta

