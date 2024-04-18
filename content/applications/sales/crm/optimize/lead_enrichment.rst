===============
Lead enrichment
===============

Lead enrichment is a service that provides business information for a contact attached to a lead.
Lead enrichment is an In-App Purchase (IAP) that requires credits to use, and is available for
existing leads in an Odoo database.

The information provided by lead enrichment can include general information about the business
(including full business name and logo), social media accounts, :guilabel:`Company type`,
:guilabel:`Founded` information, :guilabel:`Sectors` information, the number of
:guilabel:`Employees`, :guilabel:`Estimated revenue`, :guilabel:`Phone` number,
:guilabel:`Timezone`, and :guilabel:`Technologies Used`.

.. note::
   Enterprise Odoo users with a valid subscription get free credits to test :abbr:`IAP (In-App
   Purchase)` features before deciding to purchase more credits for the database. This includes
   demo/training databases, educational databases, and one-app-free databases.

Set up lead enrichment
======================

To set up lead enrichment in the *CRM* application, navigate to :menuselection:`CRM app -->
Configuration --> Settings`. Under the :guilabel:`Lead Generation` section, tick the box next to
:guilabel:`Lead Enrichment`, and select either :guilabel:`Enrich leads on demand only` or
:guilabel:`Enrich all leads automatically`. :guilabel:`Save` the changes.

.. image:: lead_enrichment/lead-enrichment-activate.png
   :align: center
   :alt: CRM lead generation settings page, with lead enrichment activation highlighted, and enrich
         leads on demand only chosen.

Enrich leads
============

Enrichment of leads is based on the domain of the email address of the customer set on the lead.
There are two different ways that a lead can be enriched: *automatically* and *manually*.

Automatically enrich leads
--------------------------

During set up, if :guilabel:`Enrich all leads automatically` was selected, then no action needs to
be taken by the user to enrich the lead. A scheduled action runs automatically, every sixty minutes,
and enrichment occurs on leads, after a remote database is contacted.

.. tip::
   To access the cron that runs for the automatic lead enrichment, activate :ref:`developer mode
   <developer-mode>`, and navigate to :menuselection:`Settings app --> Technical menu --> Automation
   --> Scheduled Actions`. In the :guilabel:`Search...` type in `partner autocomplete`. Click into
   the result labeled :guilabel:`Partner Autocomplete Sync with remote DB`, and make any necessary
   adjustments. In the :guilabel:`Execute Every` field, enter a value greater than or equal to five
   minutes.

.. example::
   The following is an example of a successful autocomplete of lead enrichment data:

   .. image:: lead_enrichment/lead-enrichment-data.png
      :align: center
      :alt: Chatter showing lead enrichment data.

Manually enrich leads
---------------------

If the :guilabel:`Enrich leads on demand only` option was selected when activating :guilabel:`Lead
Enrichment`, each lead that a user wishes to enrich will need to be manually enriched. This is
achieved by clicking the :guilabel:`Enrich` button in the top menu of the lead.

The same information will be retrieved at the same :abbr:`IAP (In-App Puchase)` credit cost (one per
enrichment). This method of enrichment is useful when every lead does not need to be enriched or
cost is an issue.

.. image:: lead_enrichment/manual-enrichment.png
   :align: center
   :alt: Manual enrich button feature highlighted on the CRM lead.

.. tip::
   Manually enrich leads in bulk using the *list* view. First navigate to the user's *CRM* pipeline
   (:menuselection: CRM app --> Sales --> My Pipeline`) and click the list view (:guilabel:`☰ (three
   horizontal lines)` icon). Next, tick the checkboxes for the leads that should be manually
   enriched. Finally, click the :guilabel:`⚙️ Actions` icon, and select :guilabel:`Enrich`.

Pricing
=======

Lead enrichment is an *In-App Purchase* feature and each enriched lead costs one credit.

.. note::
   See here for full pricing information: `Lead Generation by Odoo IAP
   <https://iap.odoo.com/iap/in-app-services/273>`_.

To buy credits, navigate to :menuselection:`CRM app --> Configuration --> Settings`. In the
:guilabel:`Lead Generation` section, under the :guilabel:`Lead Enrichment` feature, click on
:guilabel:`Buy Credits`.

.. image:: lead_enrichment/buy-lead-enrichment-credits-setting.png
   :align: center
   :alt: Buy credits from the lead enrichment settings.

Credits and balances may also be purchased by navigating to :menuselection:`Settings --> General
Settings`. In the :guilabel:`In-App Purchases` section, under the :guilabel:`Odoo IAP` feature,
click on :guilabel:`View My Services`.

.. image:: lead_enrichment/view-my-services-setting.png
   :align: center
   :alt: Buy credits in the Odoo IAP settings.

.. seealso::
   :doc:`../../../essentials/in_app_purchase`

.. important::
   When collecting a company's contact information, make sure to be aware of the latest EU
   regulations, get more information about General Data Protection Regulation on `Odoo GDPR
   <http://odoo.com/gdpr>`__.
