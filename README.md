Opencart
========

Opencart Libraries and Extentions used by [mAsT3RpEE's Zone][1]


#### Install ####

1.  [Dowload][2] and install [VQMod][3]
2.  Add currency column to products table
    
    > ALTER TABLE oc_product ADD currency VARCHAR( 3 ) NOT NULL AFTER price;
    
3.  [Download][4] archive and copy contents of upload folder to opencart directory


#### TODO ####
*   Add support for specials
*   Add support for openbay
*   Add support for play
*   Add support for amazonaws
*   Add support for ebay


Libraries
---------

None

Extentions
----------
*   **[product_option_currency](upload/vqmod/xml/product_option_currency.xml):**  
    VQMod extention that allows you to select the currency of a product price
    
*   **mod_yahoo_finance:**  
    VQMod that adds yahoo finance API functionality to OpenCart


   [1]: http://mast3rpee.tk                                                         "mAsT3RpEE's Zone"
   [2]: https://code.google.com/p/vqmod/                                            "VQMod Home Page"
   [3]: https://code.google.com/p/vqmod/wiki/Install_OpenCart                       "VQMod Install Instructions"
   [4]: https://github.com/mAsT3RpEE/Opencart/archive/product_option_currency.zip   "Download"
