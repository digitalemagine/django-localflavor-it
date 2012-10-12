=====================
django_localflavor_it
=====================

Country-specific Django helpers for Italy.

What's in the Italy localflavor?
================================

* forms.ITSocialSecurityNumberField: A form field that validates input as an
  Italian social security number (`codice fiscale`_).

* forms.ITVatNumberField: A form field that validates Italian VAT numbers
  (partita IVA).

* forms.ITZipCodeField: A form field that validates input as an Italian zip
  code. Valid codes must have five digits.

* forms.ITProvinceSelect: A ``Select`` widget that uses a list of Italian
  provinces as its choices.

* forms.ITRegionSelect: A ``Select`` widget that uses a list of Italian regions
  as its choices.

.. _codice fiscale: http://www.agenziaentrate.gov.it/wps/content/Nsilib/Nsi/Home/CosaDeviFare/Richiedere/Codice+fiscale+e+tessera+sanitaria/Richiesta+TS_CF/SchedaI/Informazioni+codificazione+pf/

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
