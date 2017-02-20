.. rtrlib-python documentation master file, created by
   sphinx-quickstart on Tue Sep 20 14:26:25 2016.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to rtrlib-python's documentation!
=========================================

rtrlib-python_ is a cffi based binding for RTRlib_.

The RTRlib implements the client-side of the RPKI-RTR protocol (RFC
6810) and BGP Prefix Origin Validation (RFC 6811). This release also
supports Internet-Draft draft-ietf-sidr-rpki-rtr-rfc6810-bis, which
enables the maintenance of router keys. Router keys are required to
deploy BGPSEC.

Currently only basic validation against one cache is supported.

Installation
------------

Requirements
''''''''''''''
- python 2.7 or python 3
- C Compiler
- RTRlib_

Python Requirements
'''''''''''''''''''
If you are using virtualenv these are installed automatically during the install step,
otherwise you have to use your platforms package management tool or just run ``pip install -r requirements.txt``.

- cffi>=1.4.0
- enum34
- six

Download and Installation
'''''''''''''''''''''''''

- ``git clone https://github.com/rtrlib/python-binding.git``
- ``cd python-binding``
- ``python setup.py build``
- ``python setup.py install``

For usage examples see here :ref:`here <Usage Examples>`
or in the tools_ dir of the repository.


.. _rtrlib-python: https://github.com/rtrlib/python-binding
.. _RTRlib: https://github.com/rtrlib/rtrlib
.. _tools: https://github.com/mroethke/rtrlib-python/tree/master/tools

Contents:

.. toctree::
   :maxdepth: 2

   api
   callbacks
   usage



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

