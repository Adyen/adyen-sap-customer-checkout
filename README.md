# adyen-sap-customer-checkout


# changelog

***2024-07-30***
* Improvement: The plugin will log at startup which version is started
* Improvement: Logout of cashier user will delete the standard terminal choice when using dynamic terminal choice is active
* Bugfix: Setting a standard terminal when no receipt was open resulted in an error

provided adyenplugin-1.0.24-FP18 - suitable for CCO FP18 to FP20  
provided adyenplugin-1.0.24-FP16 - suitable for CCO FP16 & FP17

***2024-04-12***  
* Improvement: Actual values of card payments are now entered automatically. Thus, there should be no discrepancies in the daily closing.  
* Improvement: Chosen standard terminal will be saved even after cashier logged out once.
* Improvement: Return of a receipt with copied payment item which was originally paid with adyen will now open the terminal choice dialog if dynamic terminal choice is active.  
* Improvement: Card mapping works now like a regex. E.g. visadebit, visa, visacredit, visa_applepay... will now be mapped with a single visa=2  
If visacredit should be mapped to another CCO card, this can be done with visa=2;visacredit=23
* Bugfix: Changing the CreditCardTypeCode could lead to an error in cashdesk closing when receipts were already posted with this card.

provided Plugin adyenplugin-1.0.23-FP18 - suitable for CCO FP18 & FP19  
provided Plugin adyenplugin-1.0.23-FP16 - suitable for CCO FP16 & FP17

***IMPORTANT***  
adyenplugin-1.0.20-FP14 is out of maintenance!


***2023-12-21***  
* Improvement: warning message when fall back terminal is used is now only shown when no dynamic terminal feature is activated.  
* Bugfix: Terminal choice was shown on every split card payment. Final payment was done on last choice. Now first choice will be used and no further dialogs appear.  

provided Plugin adyenplugin-1.0.20-FP18  
provided Plugin adyenplugin-1.0.20-FP16  
provided Plugin adyenplugin-1.0.20-FP14

***2023-09-06***  
provided Plugin adyenplugin-1.0.12-FP16 - suitable for CCO FP16 and FP17
  
***2023-08-25***  
provided Plugin adyenplugin-1.0.12-FP16 - suitable for CCO FP16  
provided Plugin adyenplugin-1.0.12-FP14 - suitable for CCO FP14 and FP15  
