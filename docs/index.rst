.. Pyramid Restful Framework documentation master file, created by
   sphinx-quickstart on Wed Feb  7 21:10:16 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Pyramid Restful Framework's (PRF) documentation
=====================================================

A RESTful API framework for Pyramid heavily influenced by `django-rest-framework <https://github.com/encode/django-rest-framework>`_.

The goal of this project is to provide DRF's view patterns on a lighter weight web framework that grants you more
fine grained and explicit control over database queries and object serialization/deserialization. This is accomplished
using `SQLAlchemy <http://www.sqlalchemy.org/>`_ as an ORM and
`marshmallow <https://github.com/marshmallow-code/marshmallow>`_ Schemas for object serialization and deserialization.

If you are familiar with django-rest-framework you should pick up pyramid-restful-framework very quickly.

.. toctree::
   :caption: User Guide

   user/quickstart
   user/configuration
   user/views
   user/generics
   user/viewsets
   user/permissions
   user/filters
   user/expandables
   user/pagination

.. toctree::
   :caption: API Guide

   api

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
