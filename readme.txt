=== WP e-Commerce Fat Zebra Gateway ===
Contributors: fatzebra
Tags: ecommerce, wp-ecommerce, fatzebra, payment gateway, australia
Requires at least: 3.3
Stable tag: trunk

The WP e-Commerce Fat Zebra Gateway plugin enabled integration with iWP e-Commerce and the Fat Zebra Payment Gateway (for Australian Merchants).

== Description ==

This plugin provides integration with WooCommerce and the Fat Zebra Payment Gateway, an Australian online payment gateway.

Tested with WP e-Commerce version 3.8 and above.

Visit [https://www.fatzebra.com.au](https://www.fatzebra.com.au "Fat Zebra Online Payment Gateway") for more details on using Fat Zebra.

== Installation ==

There are two methods to install the plugin:

**Copy the file to the WordPress plugins directory:**

1. Make a new directory in [SITE_ROOT]/wp-content/plugins called woocommerce-fat-zebra-gateway
2. Copy the file wp-e-commerce-fatzebra.php to this new directory.
3. Activate the newly installed plugin in the WordPress Plugin Manager.


**Install the plugin from WordPress:**

1. Search for the WP e-Commerce Fat Zebra plugin from the WordPress Plugin Manager.
2. Install the plugin.
3. Activate the newly installed plugin.

== Configuration ==

1. Visit the Store settings page, and click on the Payments tab.
2. Tick the check box for Fat Zebra then click the Edit link.
3. Enter your Username and Password and click Update.

You should now be able to test the purchases via Fat Zebra.

== Changelog ==

= 1.0 =
* Initial release

= 1.0.1 = 
* Bug fix for test/sandbox mode options
* Option to add Fat Zebra logo

= 1.0.2 = 
* Added card logos

= 1.0.3 = 
* Fixed bug where 'string' booleans were being sent rather then native bools, causing test mode to be used

== Support ==

If you have any issue with the Fat Zebra Gateway for WooCommerce please contact us at support@fatzebra.com.au and we will be more then happy to help out.
