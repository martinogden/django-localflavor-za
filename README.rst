=====================
django_localflavor_za
=====================

Country-specific Django helpers for South Africa.

What's in the South Africa localflavor?
=======================================

* forms.ZAIDField: A form field that validates input as a South African ID
  number. Validation uses the Luhn checksum and a simplistic (i.e., not
  entirely accurate) check for birth date.

* forms.ZAPostCodeField: A form field that validates input as a South African
  postcode. Valid postcodes must have four digits.

* forms.ZAProvinceSelect: A Select widget that uses a list of South African
  provinces and territories as its choices.

See the source code for full details.

About localflavors
==================

Django's "localflavor" packages offer additional functionality for particular
countries or cultures.

For example, these might include form fields for your country's postal codes,
phone number formats or government ID numbers.

This code used to live in Django proper -- in django.contrib.localflavor -- but
was separated into standalone packages in Django 1.5 to keep the framework's
core clean.

For a full list of available localflavors, see https://github.com/django/
