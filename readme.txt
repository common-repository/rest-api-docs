=== REST API Docs ===

Contributors: tarosky,Takahashi_Fumiki  
Donate link: https://tarosky.co.jp/  
Tags: rest  
Requires at least: 4.7  
Tested up to: 4.9.4  
Stable tag: 0.2.0  
License: GPLv3 or later  
License URI: https://www.gnu.org/licenses/gpl-3.0.html

A REST API documentation tool.

== Description ==

This plugin shows you available REST API endpoints.
You can find availability of your WordPress easily.

== Installation ==

Installing via WordPress admin screen is recommended.
You can find **Tools > REST API** menu.

= Manual Installation =

1. Upload rest-api-docs folder in `wp-content/plugins` folder.
1. Activate the plugin through the 'Plugins' menu in WordPress

= Build from Source =

This plugin is also hosted on [Github](https://github.com/kuno1/rest-api-docs).
To build this plugin, follow the instructions below. [npm](https://www.npmjs.com) is required.

<pre>
#Clone repository.
git clone git@github.com:kuno1/rest-api-docs.git
cd rest-api-docs
#Build assets and remove unnecessary files.
./bin/package.sh
</pre>

== Frequently Asked Questions ==

= How can I report bugs? =

Post to support forum or create issue on [github](https://github.com/kuno1/rest-api-docs/issues).

== Screenshots ==

W.I.P

== Changelog ==

= 0.2.0 =

* Add automatic deploy.
* Change plugin name with "s".

= 0.1.0 =

* Initial release.
