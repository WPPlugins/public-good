=== Public Good ===
Contributors: dratner
Donate link: https://publicgood.com/
Tags: take action, do public good, nonprofit, charity, fundraising, social media
Requires at least: 3.0.1
Tested up to: 4.4
Stable tag: 1.4.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin lets you embed Take Action buttons in your content to allow readers to engage with nonprofits working on the causes you write about.

== Description ==

The Public Good [Take Action Button](http://blog.publicgood.com/post/129584365845/what-is-the-take-action-button) (TAB)
provides readers with an alternative to simply sharing content on social media.
It is meant to be included in articles that talk about causes or issues in society and it gives readers the opportunity
to change the story by supporting organizations working on the cause the content is discussing.

By default, Public Good will provide a list of relevant organizations, but if you desire you can "hint" or indicate a specific set of organizations
you'd like people to see via the cause property.

Support for donations buttons for individual charities will be added soon.

== Installation ==

1. Upload `publicgood.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. (Optional) Contact Public Good for a source identifier. This will allow you to track who clicks the button and chooses to support a cause.
4. (Optional) Go to 'Settings' menu in WordPress and select the 'Public Good' submenu. You can put your source identifier here and also a default location.
5. Use the Take Action Button shortcode `[takeaction]` wherever you want the button to appear.
6. (Optional) If you want to point to a specific cause using a shortcode with a hint: [takeaction keywords="Clean Water"]

== Frequently Asked Questions ==

= What is the Take Action Button? =

Find out [here](http://blog.publicgood.com/post/129584365845/what-is-the-take-action-button).

= Can publishers get paid for using the Take Action Button? =

Larger publishers can get paid for using the button.
Please [contact us](https://publicgood.zendesk.com/hc/en-us/requests/new) for more information.

= How do I get a source identifier for my Take Action Buttons? =

Please [contact us](https://publicgood.zendesk.com/hc/en-us/requests/new) and we'll issue one.

= I see a script being loaded from pgs.io. What's that? =

pgs.io is Public Good's content distribution network (CDN). It's designed to make sure the button script loads quickly.

= Why is there an outside dependency? Can I load all this on my site? =

We host the script behind the button because we are constantly optimizing and improving how it does matches
and interacts with content. While you can technically use a cached version on the script, you'd lose the benefits
of these improvements between plugin upgrades.

== Screenshots ==

1. TAB_Screen_Shot.png

== Changelog ==

= 1.4.1 =
* Fixed incorrect identification of target type.

= 1.4 =
* Add Public Good as an oEmbed provider.

= 1.3 =
* Upgrade plugin to use version 2 of the button code.

= 1.2 =
* Security enhancements to support Wordpress VIP
* Added support for different sizes and colors of buttons

= 1.1.3 =
* Fixed to support WP versioning

= 1.1.1 =
* Updates to readme

= 1.1 =
* Added default location as an option.
* Added using tags to help determine a default cause if none is specified.

= 1.0 =
* First stable version!

== Upgrade Notice ==

= 1.3 =
Updates to support version 2 of the button, including new visual treatment and cofiguration options.

= 1.1.3 =
This is just a versioning support change - not critical if you are on 1.1.1

= 1.1.1 =
You can now specify a default location and the button is tag-aware.

= 1.0 =
This is the first stable version. All previous are for testing only.


