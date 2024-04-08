=====================
Print shipping labels
=====================

.. |DO| replace:: :abbr:`DO (Delivery Order)`

Integrate Odoo with :doc:`third-party shipping carriers
<../setup_configuration/third_party_shipper>` to automatically generate shipping labels that
includes prices, destination addresses, tracking numbers, and barcodes.

Configuration
=============

To generate labels for a third-party shipping carrier, install the shipping connector, configure and
activate the delivery method, and provide the company's :ref:`source address
<inventory/shipping_receiving/configure-source-address>` and :ref:`product weights
<inventory/shipping_receiving/configure-weight>`.

For detailed instructions and context on configuring these options, refer to :doc:`this document
<../setup_configuration/third_party_shipper>`.

Install shipping connector
--------------------------

Install the shipping connector's module in Odoo to integrate Odoo with the third-party shipping
carrier. To do so, navigate to :menuselection:`Inventory app --> Configuration --> Settings`.

Under the :guilabel:`Shipping Connectors` heading, select the third-party shipping carrier's
checkbox to install it. Multiple shipping connectors may be selected. Then, click :guilabel:`Save`.

.. image:: ../setup_configuration/third_party_shipper/shipping-connectors.png
   :align: center
   :alt: Options of available shipping connectors in Odoo.

Delivery method
---------------

Next, add the carrier details by going to :menuselection:`Inventory app --> Configuration -->
Shipping Methods`.

On the :guilabel:`Shipping Methods` page, choose the desired delivery method. For details on
configuring the third party shipping method, go to:

.. seealso::
   - :doc:`Configure third-party carrier <../setup_configuration/third_party_shipper>`
   - :doc:`DHL credentials <../setup_configuration/dhl_credentials>`
   - :doc:`Sendcloud credentials <../setup_configuration/sendcloud_shipping>`
   - :doc:`UPS credentials <../setup_configuration/ups_credentials>`

Then, select the :guilabel:`Get Rate and Create Shipment` option in the :guilabel:`Integration
Level` field to ensure the shipping label gets printed.

.. image:: labels/integration-level.png
   :align: center
   :alt: Set the "Get Rate and Create Shipment" option.

Production environment
~~~~~~~~~~~~~~~~~~~~~~

With the delivery method details configured, click the :guilabel:`Test Environment` smart button to
set it to production environment.

.. warning::
   Setting the delivery method to :guilabel:`Production` creates **real** shipping labels, and users
   are at risk for being charged through their carrier account (e.g., UPS, FedEx), **before** users
   charge customers for shipping. Verify all configurations are correct before launching the
   delivery method to :guilabel:`Production`.

.. image:: ../setup_configuration/third_party_shipper/production.png
   :align: center
   :alt: Show the "Test Environment" smart button.

Print tracking labels
=====================

Tracking labels are generated after the delivery order (DO) is validated. Begin by creating a
quotation, adding the shipping cost, confirming the sales order, and then validating the |DO|.

Add shipping on quotation
-------------------------

To generate a tracking label for an order, begin by creating a quotation in :menuselection:`Sales
app --> Orders --> Quotations`. Then, click the :guilabel:`Add Shipping` button in the bottom-right
corner of the quotation.

.. image:: labels/add-shipping-button.png
   :align: center
   :alt: Show the "Add Shipping" button on the quotation.

In the resulting pop-up window, select the intended carrier from the :guilabel:`Shipping Method`
drop-down menu. Clicking :guilabel:`Get Rate` displays the shipping cost for the customer via the
third-party carrier in the :guilabel:`Cost` field.

.. important::
   If clicking :guilabel:`Get Rate` results in an error, ensure the :ref:`warehouse's address
   <inventory/shipping_receiving/configure-source-address>` and :ref:`weight of products in the
   order <inventory/shipping_receiving/configure-weight>` are properly configured.

Click :guilabel:`Add` to add the cost to the quotation, which is listed as the :ref:`configured
delivery product <inventory/shipping_receiving/delivery-product>`. Finally, click
:guilabel:`Confirm` on the quotation, and click the :guilabel:`Delivery` smart button to access the
|DO|.

.. image:: labels/get-rate.png
   :align: center
   :alt: Show "Get rate" pop-up window.

.. tip::
   For users who do not have the *Sales* app installed, the shipping carrier is specified in a
   delivery order's :guilabel:`Carrier` field of the :guilabel:`Additional Info` tab.

   .. image:: labels/additional-info-tab.png
      :align: center
      :alt: Show the "Additional Info" tab of a delivery order.

Validate delivery order
-----------------------

On the delivery order, after the items in the order have been packed, click :guilabel:`Validate` to
get the shipping carrier's tracking number and generate the shipping label.

The :guilabel:`Tracking Reference` number is generated in the :guilabel:`Additional Info` tab of the
delivery order. Click the :guilabel:`Tracking` smart button to access the tracking link from the
shipping carrier's website.

The tracking label is found in PDF format in the chatter.

.. image:: labels/shipping-label.png
   :align: center
   :alt: Show generated shipping label in the chatter.

.. note::
   For multi-package shipping, one label is generated per package. Each label appears in the
   chatter.

.. figure:: labels/sample-label.png
   :align: center
   :alt: Sample label generated from Odoo's shipping connector with FedEx.

   Sample label generated from Odoo's shipping connector with FedEx.

.. seealso::
   - :doc:`invoicing`
   - :doc:`multipack`
