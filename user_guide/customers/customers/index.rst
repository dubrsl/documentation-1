.. _user-guide--customers:

Customers
=========

.. begin

.. contents:: :local:

In Customer section you can manage the customers who represent a group of buyers related to the same business organization: add a new customer and view, edit and delete existing customers, and access the aggregated information about customer users activities and eCommerce operations (requests for quotes, quotes, and sales orders).

You can also quickly get to the :ref:`customer organization structure <user-guide--customers--customers--organize>`, :ref:`an address book <user-guide--getting-started--address-book>` with a preview on the map, :ref:`customer users <user-guide--customers--customer-users>`:, :ref:`price lists <user-guide--customers--customer-groups--pricelist>` enabled for the customer, and overview of :ref:`requests for quote <user-guide--sales--requests-for-quote>`, :ref:`sales orders <user-guide--sales--orders>`, :ref:`quotes <user-guide--sales--quotes>` created by and for customer users. Finally, you can get to a summary of activity from every operation triggered by the customer users.

.. image:: /user_guide/img/customers/customers/Customers.png
   :alt: The list of all customers available in the system

.. include:: /user_guide/customers/customers/create.rst
   :start-after: begin
   :end-before: stop

.. note:: Keep in mind that customers with at least one successful registered checkout cannot be deleted from the system.

.. image:: /user_guide/img/customers/customers/unable_to_delete_customers.png
   :alt: A note appears when deleting a customer warning that no entities can be deleted

Export
------

You can export the customer details in the .csv format following the :ref:`Exporting Bulk Items <export-bulk-items>` guide.

Import
------

You can import the bulk details of updated or processed customer information in the .csv format following the steps described in the :ref:`Importing Customers <import-customers>` guide.

.. finish

**Related Articles**

* :ref:`Customer Organization Structure <user-guide--customers--customers--organize>`

* :ref:`Manage Address Book <user-guide--getting-started--address-book>`


.. toctree::
   :maxdepth: 1
   :hidden: 
  
   create
   organize
   manage_address_book