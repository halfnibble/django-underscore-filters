Documentation for: django-underscore-filters templatetags
=========================================================

These filters allow django template use of elements beginning with an underscore character.

Purpose:
--------

The sole purpose of these filters are to allow operations with template elements that naturally start with the underscore ('_') character.




Usage
=====

Form Fields
-----------

Usage: ``field_``

Example::

   {{ form|field_:'_field_name' }}

Attributes
----------

Usage: ``attr_``

Example::
   
   {{ my_tag|attr_:'_attr_name' }}

Dictionary Keys
---------------

Usage: ``dict_``

Example::
   
   {{ my_dict|dict_:'_key_name' }}
