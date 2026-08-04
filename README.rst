PGPym: Pretty Good Privacy for Python
=====================================

.. image:: https://badge.fury.io/py/PGPy.svg
    :target: https://badge.fury.io/py/PGPy
    :alt: Latest stable version

.. image:: https://travis-ci.com/SecurityInnovation/PGPy.svg?branch=master
    :target: https://travis-ci.com/SecurityInnovation/PGPy?branch=master
    :alt: Travis-CI

.. image:: https://coveralls.io/repos/github/SecurityInnovation/PGPy/badge.svg?branch=master
    :target: https://coveralls.io/github/SecurityInnovation/PGPy?branch=master
    :alt: Coveralls

.. image:: https://readthedocs.org/projects/pgpy/badge/?version=latest
    :target: https://pgpy.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

`PGPym` is a fork of `PGPy` with additional maintenance fixes.
`PGPy` is Python library for implementing Pretty Good Privacy into Python programs, conforming to the OpenPGP specification per RFC 4880.
`PGPym` installs with the same import package name, and is backwards import compatible with the original package.


Features
--------

Currently, PGPy can load keys and signatures of all kinds in both ASCII armored and binary formats.

It can create and verify RSA, DSA, and ECDSA signatures, at the moment. It can also encrypt and decrypt messages using RSA and ECDH.

PGPym Specific Features
~~~~~~~~~~~~~~~~~~~~~~~

The following changes are specific to `PGPym`:

* patched to be compatible with Python 3.13.
* support setting key expiration dates for PGP subkeys.

Installation
------------

To install PGPym, simply:

.. code-block:: bash

    $ pip install PGPym

Documentation
-------------

`PGPy Documentation <https://pgpy.readthedocs.io/en/latest/>`_ on Read the Docs

Discussion
----------

Please report any bugs found on the `issue tracker <https://github.com/eaaltonen/PGPy/issues>`_

You can also join ``#pgpy`` on Freenode to ask questions or get involved

Requirements
------------

- Python >= 3.6

  Tested with: 3.14, 3.13, 3.12, 3.11, 3.10

- `Cryptography <https://pypi.python.org/pypi/cryptography>`_

- `pyasn1 <https://pypi.python.org/pypi/pyasn1/>`_

- `six <https://pypi.python.org/pypi/six>`_

License
-------

BSD 3-Clause licensed. See the bundled `LICENSE <https://github.com/SecurityInnovation/PGPy/blob/master/LICENSE>`_ file for more details.
