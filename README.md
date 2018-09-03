=== Maintenance Mode ===
Contributors: CLEANCODED
Tags: maintenance-mode maintenance
Requires at least: 4.6
Tested up to: 4.7
Stable tag: 0.2.1
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Shut down your site for a little while and do some maintenance on it!

== Description ==

Usage:
 - Add a template to your theme's root folder called `template-maintenance-mode.php`.
 - This should be a simple HTML page that should include the message you want to show your visitors.
 - Note: the template should include `wp_head()` and `wp_footer()` calls.
 - Add the VIP_MAINTENANCE_MODE constant to your theme and set to `true`.

== Installation ==

1. Install the plugin.
1. Set the `VIP_MAINTENANCE_MODE` constant to true.
1. Activate.

== Changelog ==
= 0.1.0 =
* Initial plugin
