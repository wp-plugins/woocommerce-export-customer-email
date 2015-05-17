=== WooCommerce Export Customer Email ===
Contributors: mitcmt
Plugin Site: http://mithu.me/
Tags: woocommerce, customer, email, export
Requires at least: 3.5
Tested up to: 4.2.2
Stable tag: 1.3
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

An essential feature for WooCommerce shop to export customer's billing emails from admin panel.


== Description ==

WooCommerce Export Customer Email simply adds a extra link under customers tab to export all customer emails into a single file. The plugin allows you to download the file to a CSV format.

= Features =

* Compatible with WooCommerce 2.0.* and 2.1.*
* Downloadable CSV file.
* Filename with store name and download time.
* All customer email (existing and new).

= Usage =

* The plugin requires [WooCommerce](http://wordpress.org/plugins/woocommerce/) to be activated in order to work. To download CSV, you must installed and activated WooCommerce first.
* After successfully installed, you'll find the option from `WooCommerce > Reports > Customers > Export customer email` into admin panel.
* If you have installed WooCommerce version before 2.1.0, you'll find the option from `WooCommerce > Reports > Export` into admin panel.


== Installation ==

1. Download the Plugin `woocommerce-export-customer-email.zip`

2. Extract zip and upload the plugin in `wp-content/plugins/` directory.

3. Activate the plugin through the plugins menu.

4. Go to WooCommerce customers tab from report page and that's it.


== Screenshots ==

1. Export customer email option


== Changelog ==

= v1.3 (17.05.2015) =
* Fixed - Error control operator added.
* Added - New class method.
* Added - Output buffering functions.
* Renamed - Class methods.
* Renamed - Class properties.
* Changed - File output stream.
* Changed - Export options to inline.
* Removed - Table fieldset.
* Updated - File pointer functions.
* Updated - HTTP headers.

= v1.2 (11.05.2015) =
* Feature - Added duplicate email remove option.
* Tested - Support for WooCommerce-2.3.8 or later.
* Tested - Compatibility up to WP-4.2.2

= v1.1 (10.04.2015) =
* Update - Backwards compat hook.
* Feature - Added coustomer name export option.
* Tested - Support for WooCommerce-2.1.0 or later.
* Tested - Compatibility up to WP-4.1.1

= v1.0.1 (25.05.2014) =
* Fix - File name with shop time.
* Change - System time with shop time.

= v1.0 (18.05.2014) =
* First release.
