# RatePAY GmbH - Magento Payment Module
============================================

|Module | RatePAY Module for Magento
|------|----------
|Author | Aarne Welschlau
|Shop Version | `CE` `1.7.x` `1.8.x` `1.9.x`
|Version | `3.0.3`
|Link | http://www.ratepay.com
|Mail | integration@ratepay.com
|Installation | see separate installation manual

## Changelog

### Version 3.0.3 - Released 2015-07-07
* changes in backend config
* CH/CHF ready
* bugfixes

### Version 3.0.2 - Released 2015-05-13
* changed invoice event from save to register

### Version 3.0.1 - Released 2015-05-04
* fixed bug in unit-price-gross calculation
* deactivated installment plan on order review

### Version 3.0.0 - Released 2015-04-13
* changed namespace und module name
* new backend configuration
* configuration via PROFILE REQUEST; includes credential and country validation
* persistent installment config (months allowed, min rate)
* support of DE and AT credentials in same sub shop
* product categories excludable
* customer groups excludable
* shipping methods excludable
* module order processes (cancel, invoice/shipment, creditmemo) seperatly deactivatable
* changed basket struktur (api v1.6)
* installment plan on order summery page
* improved IBS/PAYMENT QUERY
* few smaller fixes and changes

### Version 2.5.1 - Released 2015-01-30
* permits shipping without invoicing
* customer block only on PR

### Version 2.5.0 - Released 2014-12-08
* fixed installment without PAYMENT CONFIRM
* no full-return anymore
* no negative basket amount anymore
* ZGB-DSE link by default
* full integration of AT support
* address normalization

### Version 2.4.5 - Released 2014-10-28
* cURL SSLVERSION to 1 (TLS1.x)

### Version 2.4.4 - Released 2014-10-22
* changed RatePAY gateway URL
* switch to interest rate in Ratenrechner

### Version 2.4.3 - Released 2014-09-05
* fixed payment method overlay
* changed PC - prevention of multiple PC
* removed pdf and email generation

### Version 2.4.2 - Released 2014-07-09
* dob bugfix and refactoring the method of input
* added validation of vat id and phone number
* added merchant cunsumer id
* changes in language files
* fixed PQ Payment Init bug
* disabled DOB in case of B2B
* fixed VatId bug and added changeable VatId form

### Version 2.4.1 - Released 2014-06-04
* bugfix in Payment Query configuration

### Version 2.4.0 - Released 2014-04-30
* added Payment Query
* extended Whitelabel mode
* fixed company-name xml tag in customer block
* removed deprecated http-header-list block in xml head
* removed agreement box (invoice/installment); not needed anymore

### Version 2.3.0 - Released 2014-04-01

* inplementation of Device Ident within main footer
* added separat upgrade file for each release version - solves troubles in case of modul updates
* added Whitelabel mode

### Version 2.2.3 - Released 2014-02-13
* minor changes in the checkout layout

### Version 2.2.2 - Released 2014-02-06
* IBAN validation without JS

### Version 2.2.1 - Released 2014-01-30
* improved IBAN validation
* changed sandbox mode - no decline of rp payment methods after negative response while sandbox mode

### Version 2.2.0 - Released 2014-01-29
* added SEPA functionality - includes IBAN and BIC fields and new text blocks
* deactivated saving of user bank account data

### Version 2.1.1 - Released 2014-01-07
* better bundle handling
* disable partial shipping refund

### Version 2.1.0 - Released 2013-11-21
* allow differing billing and shipping addresses
* send customer name and company (if necessary) within shipping address

### Version 2.0.9 - Released 2013-11-20
* remove bundle article from requests and send only the bundled items
* fix guest checkout elv data saving problem

### Version 2.0.8 - Released 2013-05-23
* fix wrong payment fee behavior after second selection of
   RatePAY

### Version 2.0.7 - Released 2012-09-04
* fix payment fee
* fix wrong email in creditmemo footer

### Version 2.0.6 - Released 2012-03-05
* fix different behavior for article bundles

### Version 2.0.5 - Released 2012-02-15
* fix wrong path for the rp footer image in the invoice
* set the _canAuthorize Payment property to "false"
* fix partial return bug

### Version 2.0.4 - Released 2012-11-07
* changed default Theme to base Theme
* fixed encryption constant Bug
* fixed a bug, where you couldn't hide payment methods

### Version 2.0.3 - Released 2012-10-23
* fix encryption UTF-8 Bug

### Version 2.0.2 - Released 2012-09-26
* fix discount tax

### Version 2.0.1 - Released xxxx-xx-xx
* add enterprise template support
* fix wrong transfer of item data after a retour
* fix missing translation for shipping error

### Version 2.0.0 * Released 2012-06-27
* use the native shop functions to invoice, refund and cancel
* add bulk cancel, refund, invoice support
* add RatePAY xml log for every order
* add config view for merchant
* add ELV support

### Version 1.4.4 * Released 2012-02-16
* fixed AGB Bug

### Version 1.4.3 * Released 2012-02-16
* added terms of use for RatePAY

### Version 1.4.2 * Released 2012-02-14
* changed AGB Check
* changed requirement for RatePAY Configs
* added default values for RatePAY Configs
* changed templates to work with Enterprise

### Version 1.4.1 * Released 2012-02-13
* fixed Mantis Bug 0000604

### Version 1.4.0 * Released 2012-02-07
* Added Payment Method RatePAY Rate

### Version 1.3.0 * Released 2012-01-23
* rewritten from scratch

## Nutzungsbedingungen
Bitte beachten Sie die Nutzungsbedingungen unter http://www.ratepay.com/nutzungsbedingungen/