.. truphone connect documentation master file, created by
   sphinx-quickstart on Thu Jan 16 14:56:03 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Introduction
========================================

Welcome to the Truphone Connect API developer documentation. Here you can find general instructions for using the API, such as authentication, test and production environments, roles and how to use each different available endpoint/resource, including example requests and possible responses.


Before you start
################

All operations are private and protected under a specific role, which is granted when subscribing the API. Different roles have access to different operations, so before starting to code your app, be sure to check what is your client/application's authorization role. Current avaliable roles are:

- Reseller - `RESELLER` - Truphone does not handle customer/CRM data
- Account Manager - `ACCOUNT_MANAGER` - Truphone handles customer/CRM data

For more details about each specific role, check the :doc:`roles` page.


.. toctree::
   :hidden:
   :maxdepth: 4
   :caption: General
   :name: general

   releasenotes
   ratelimits
   authentication
   roles
   environments
   conventions

.. toctree::
   :hidden:
   :maxdepth: 4
   :caption: Recipes
   :name: recipes

   recipes/new-esim

.. toctree::
   :hidden:
   :maxdepth: 4
   :caption: Connectivity Management
   :name: connectivity

   reference/orders
   reference/products
   reference/sims
   reference/subscriptions
   reference/notifications

.. toctree::
   :hidden:
   :maxdepth: 4
   :caption: Customer Management
   :name: customer

   reference/customer