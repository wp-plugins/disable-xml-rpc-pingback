=== XML-RPC DDoS Protection ===
Contributors: samuelaguilera
Tags: xml-rpc, xml, rpc, pingback
Requires at least: 3.8.1
Tested up to: 4.0
Stable tag: 1.0
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Stops abuse of your site's XML-RPC by simply removing some methods used by attackers. While you can use the rest of XML-RPC methods.

== Description ==

Stops abuse of your site's XML-RPC by simply removing some methods used by attackers. While you can use the rest of XML-RPC methods.

This is more friendly than disabling totally XML-RPC, that it's needed by some plugins and apps (I.e. Mobile apps or some Jetpack's modules).

= Features =

Removes the following methods from XML-RPC interface.

* pingback.ping
* pingback.extensions.getPingbacks
* wp.getUsersBlogs

= Requirements =

* WordPress 3.8.1 or higher.
    	
== Installation ==

* Extract the zip file and just drop the contents in the <code>wp-content/plugins/</code> directory of your WordPress installation (or install it directly from your dashboard) and then activate the plugin from Plugins page.
* There's not options page, simply install and activate.
  
== Changelog ==

= 1.0 =

* Initial release.
