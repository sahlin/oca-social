.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
    :target: https://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3

==========================
Drag & drop emails to Odoo
==========================

This module was written to allow users to drag&drop emails from their desktop to Odoo.

It supports as well RFC822 .eml files as Outlook .msg (those only if `an extra library <https://github.com/mattgwwalker/msg-extractor>`_ is installed) files.

Usage
=====

To use this module, you need to:

#. save your emails on the desktop / somewhere in the file system
#. drag them to your browser, and drop them on the chatter of the record you want to attach your email to

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
    :alt: Try me on Runbot
    :target: https://runbot.odoo-community.org/runbot/205/10.0

Known issues / Roadmap
======================

* most mail clients won't allow you to drag mails directly from the mail client, you'll need some plugin for that
* for corporate environments, it might be feasible to support imap URLs and get the mail in question on the server side

Bug Tracker
===========

Bugs are tracked on `GitHub Issues
<https://github.com/OCA/social/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
=======

Images
------

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.

Libraries
---------

* `msg-extractor <https://github.com/mattgwwalker/msg-extractor>`_

Contributors
------------

* Holger Brunn <hbrunn@therp.nl>

Do not contact contributors directly about help with questions or problems concerning this addon, but use the `community mailing list <mailto:community@mail.odoo.com>`_ or the `appropriate specialized mailinglist <https://odoo-community.org/groups>`_ for help, and the bug tracker linked in `Bug Tracker`_ above for technical issues.

Maintainer
----------

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.
