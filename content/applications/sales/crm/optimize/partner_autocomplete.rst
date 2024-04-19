==============================================
Enrich contacts base with partner autocomplete
==============================================

Partner Autocomplete helps to enrich the contacts database with corporate data. Select one of the
companies suggested in the dropdown, and quickly get all the information.

Configuration
=============

Go to :menuselection:`Settings --> Contacts` and activate the *Partner Autocomplete* feature.

.. image:: partner_autocomplete/settings-partner-autocomplete.png
   :align: center
   :alt: View of settings page and the activations of the feature in Odoo

Enrich contacts with corporate data
===================================

| From any module, once a new contact is entered and the user is typing the name of it, the system
  will suggest a potential match. If it is selected, the contact will be populated with corporate
  data.

| For example, after typing *Odoo*, the following information will populate:

.. image:: partner_autocomplete/odoo-autocomplete.png
   :align: center
   :alt: Creating a new contact in Odoo

.. image:: partner_autocomplete/odoo-info-autocomplete.png
   :align: center
   :alt: View of the information being shown about odoo with the autocomplete option in Odoo

.. tip:: Partner Autocomplete also works if a VAT number is entered instead of a company name.

Pricing
=======

*Partner Autocomplete* is an *In-App Purchase (IAP)* service, which requires prepaid credits to be
used. Each request will consume one credit.

To buy credits, go to :menuselection:`Settings --> Contacts --> Partner Autocomplete or Odoo IAP
--> View My Services` and select a package.

.. note::
   - If the database runs out of credits, the only information that will be populated when clicking
     on the suggested company will be the website link and the logo.

   - Learn about our *Privacy Policy* `here <https://iap.odoo.com/privacy#header_2>`_.

.. note::
   Enterprise Odoo users with a valid subscription get free credits to test :abbr:`IAP (In-App
   Purchase)` features before deciding to purchase more credits for the database. This includes
   demo/training databases, educational databases, and one-app-free databases.

.. important::
   When getting a company's contact information make sure to be aware of the latest EU regulation,
   get more information about General Data Protection Regulation on `Odoo GDPR
   <http://odoo.com/gdpr>`__.

.. seealso::
   :doc:`../../../essentials/in_app_purchase`
