======================
 Website sale autopay
======================

Installation
============

* For multi-company only:

  Install this module https://github.com/OCA/website/tree/8.0/website_sale_order_company
  

Configuration
=============

* Install ``payment_`` module that you need to use in website shop, e.g. payment_paypal.
* From ``Settings / Payments / Payment Acquirers`` create payment acquirers.

  * In acquirer configuration select proper payment method

* For multi-company:

  * Define company for each of your products.
  * Create accounts from ``Settings / Configuration / Invoicing`` menu:

    * select template
    * select currency. WARNING: select the same currency for all companies
    * push ``[Apply]`` button

  * Create payment acquirers for each company you have.

    * In acquirer configuration select proper payment method
 
Usage
=====

Originally you need to create invoices manually every time after web sales that is not convenient.
This module creates corresponding fully filled and confirmed invoice automatically.

