django-underscore-filters
=========================

These filters allow django template use of elements beginning with an underscore character.

Purpose
-------
The sole purpose of these filters are to allow operations with template elements
that naturally start with the underscore ('_') character.

Form Fields
----------
Usage: `field_`

Example:
```python
{{ form|field_:'_field_name' }}
```

Attributes
----------
Usage: `attr_`

Example:
```python
{{ my_tag|attr_:'_attr_name' }}
```

Dictionary Keys
----------
Usage: `dict_`

Example:
```python
{{ my_dict|dict_:'_key_name' }}
```

References
----------
http://stackoverflow.com/questions/6676045/accessing-couchdbs-uuid-in-django-templates
http://stackoverflow.com/questions/13693888/accessing-dict-elements-with-leading-underscores-in-django-templates
