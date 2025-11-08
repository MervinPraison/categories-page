=== Categories Page ===
Contributors: mervinpraison
Donate link: https://mer.vin
Tags: categories, category, taxonomy, shortcode, seo
Requires at least: 3.0
Tested up to: 6.8
Stable tag: 1.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Displays a table listing of all Categories registered on your website. Shortcode.

== Description ==

Add the List of Registered Categories on to a page on your website

= Shortcode =
<code>[get_categories]</code>

More info : <a href="https://mer.vin" >Mervin Praison</a>

== Installation ==

1. Upload the full directory to wp-content/plugins
2. Activate plugin Categories Page in plugins administration
3. Add the shortcode [get_categories] on to the page you wanted it to get displayed
4. You are done!

== Frequently Asked Questions ==

= How to install? =
Follow the installation steps above.

== Changelog ==

= 1.3 =
* Security: Fixed deprecated create_function() usage (PHP 8.0+ compatibility)
* Security: Added proper escaping to all output
* Security: Fixed SQL injection vulnerability with wpdb->prepare()
* Security: Sanitized $_SERVER['REQUEST_URI'] input
* Improved: Added version numbers to enqueued scripts and styles
* Improved: Added translators comments for i18n strings
* Improved: Updated license to GPLv2 or later
* Improved: WordPress 6.8 compatibility
* Fixed: Proper text domain usage throughout

= 1.2 =
* Previous version

= 1.0 =
* Initial release

== Upgrade Notice ==

= 1.3 =
CRITICAL UPDATE: Fixes PHP 8.0+ compatibility and security vulnerabilities. Please update immediately.

Add <code>[get_categories]</code> on to the page you wanted you Categories to get displayed

== Screenshots ==

1. Shortcode being added on to the content area.

== Changelog ==

= 1.0 =
* Initial release.

== Upgrade Notice ==

= 1.0 =
* Initial Release

== Version history ==

= Version 1.0 =

* Initial release version.

== License ==

GPL2 
