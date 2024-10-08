=== Wufoo Shortcode ===

Contributors: apetrevski
Plugin Name: Wufoo Shortcode
Plugin URI: https://www.wufoo.com
Tags: wufoo, form, shortcode
Requires at least: 2.6
Tested up to: 6.0
Stable tag: 1.55
Version: 1.55

Allows the use of a special short code [wufoo] for embedding Wufoo forms.

== Description ==

Allows the use of a special short code [wufoo] for embedding Wufoo forms. It's best to grab the shortcode from the Wufoo Code Manager.

**Example:**
`[wufoo username="examples" formhash="z7w4r7" autoresize="true" height="517" header="show" ssl="true"]`

For advanced users, you can pre-set Wufoo form values with an extra parameter:
`defaultv="Field1=Bob&Field2=Sandwich Eater"`

== Installation ==

For old school manual installation people: copy the folder "wufoo_shortcode" into the /wp-content/plugins/ folder. Then go to the Plugins area of the Admin and activate. Otherwise, search for "Wufoo Shortcode Plugin" from the admin area of your WordPress site in Plugins > Add New.

== Screenshots ==

1. Usage of shortcode example
2. Where to get shortcode

== Changelog ==

1.0 - Initial release.

1.1 - SSL param isn't included in snippet if not passed. Gratis and Ad Hoc Wufoo users don't use that param, as SSL is not offered.

1.2 - Adding ability to pre-set fields via extra Default Values parameter

1.3 - Added no JavaScript fallback

1.4 - Making JavaScript embed async

1.41 - Bugfix: stop hardcoding subdomain

1.42 - Improvements to plugin

1.43 - Top level navigation support for chromium based browsers

1.46 - Fix insecure links generation

1.47 - Fix hyperlink execution in forms

1.48 - Fix XSS vulnerability

1.49 - Minor improvements

1.50 - Minor improvements

1.51 - Fix XSS vulnerability

1.52 - Security improvements

1.53 - autoresize fix

1.54 - Form path to query parameters fix

1.55 - Minor improvements

== Frequently Asked Questions ==

**What is Wufoo?**

[Wufoo](http://wufoo.com) is a web app that helps anybody build amazing online forms. It's great for busy people who need to collect data or payments quickly, but don't want to deal with programming or servers.

**Why is this useful?**

Shortcodes are clean! You can already copy and paste JavaScript or iframe code to embed a Wufoo form onto a WordPress page, but you need to make sure to be in the "HTML" tab of the writing area. If a user is in the "Visual" (default) tab, the embed code will not work. Short codes will work either way.

This plugin duplicates what is already possible on WordPress.com.
