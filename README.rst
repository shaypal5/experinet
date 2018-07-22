experinet
#######
.. |PyPI-Status| |PyPI-Versions| |Build-Status| |Codecov| |LICENCE|

.. .. |experinet_icon| image:: https://github.com/shaypal5/experinet/blob/88d480fd90820ea58c062029ce7e926201794e47/experinet_small.png

Synthetic network theory experiment.

.. code-block:: python

  >>> experinet.run_experiment(
    {
        'entry': {
            'type': 'generate',
            'model': 'ba',
            'd': 2,
        }
    }

.. contents::

.. section-numbering::


Installation
============

.. code-block:: bash

  pip install experinet
  


Features
========

* Pure python.
* Supports Python 3.5+.
* Fully tested.


Use
===

TBA


Contributing
============

Package author and maintainer is Shay Palachy (shay.palachy@gmail.com); You are more than welcome to approach him for help. Contributions are very welcomed.

Installing for development
----------------------------

Clone:

.. code-block:: bash

  git clone git@github.com:shaypal5/experinet.git


Install in development mode, including test dependencies:

.. code-block:: bash

  cd experinet
  pip install -e '.[test]'



Running the tests
-----------------

To run the tests use:

.. code-block:: bash

  cd experinet
  pytest


Adding documentation
--------------------

The project is documented using the `numpy docstring conventions`_, which were chosen as they are perhaps the most widely-spread conventions that are both supported by common tools such as Sphinx and result in human-readable docstrings. When documenting code you add to this project, follow `these conventions`_.

.. _`numpy docstring conventions`: https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt
.. _`these conventions`: https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt

Additionally, if you update this ``README.rst`` file,  use ``python setup.py checkdocs`` to validate it compiles.


Credits
=======

Created by Shay Palachy (shay.palachy@gmail.com).


.. |PyPI-Status| image:: https://img.shields.io/pypi/v/experinet.svg
  :target: https://pypi.python.org/pypi/experinet

.. |PyPI-Versions| image:: https://img.shields.io/pypi/pyversions/experinet.svg
   :target: https://pypi.python.org/pypi/experinet

.. |Build-Status| image:: https://travis-ci.org/shaypal5/experinet.svg?branch=master
  :target: https://travis-ci.org/shaypal5/experinet

.. |LICENCE| image:: https://github.com/shaypal5/experinet/blob/master/mit_license_badge.svg
  :target: https://github.com/shaypal5/experinet/blob/master/LICENSE
  
.. https://img.shields.io/github/license/shaypal5/experinet.svg

.. |Codecov| image:: https://codecov.io/github/shaypal5/experinet/coverage.svg?branch=master
   :target: https://codecov.io/github/shaypal5/experinet?branch=master
