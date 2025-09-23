.. image:: ../images/otobo-logo.png
   :align: center

.. toctree::
    :maxdepth: 2
    :caption: Contents

Overview
========
Summary
-------
This package provides a feature to inform with a given number of days in advance about a user going out of office.

Configuration
=============

System requirements
-------------------

Framework
^^^^^^^^^
OTOBO 11.0.x

Packages
^^^^^^^^
Not applicable

Third-party software
^^^^^^^^^^^^^^^^^^^^
Not applicable

Basic Configuration
-------------------
After installation, if the DaysInAdvance system configuration setting is enabled and set to a value greater than zero, the message alerting in advance of the out-of-office status is automatically shown as part of the user name.

Custom Configuration and Advanced Features
------------------------------------------
Not applicable

Configuration Reference
-----------------------
Frontend::Base
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
PreOutOfOfficeMessageTemplate
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
Defines an out of office message template to display some days in advance to getting out of office. Two string parameters (%s) available: start date and end date.

PreOutOfOfficeDaysInAdvance
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
Number of days in advance to display the previous out of office message, value 0 disables the message.

About
=======

Contact
-------
| Rother OSS GmbH
| Email: hello@otobo.io
| Web: https://otobo.io

Version
-------
Author: |doc-vendor| / Version: |doc-version| / Date of release: |doc-datestamp|
