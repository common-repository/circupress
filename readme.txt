=== CircuPress ===
Contributors: cadamsmall, douglaskarr, mikeafy
Tags: email, subscription, newsletter, email marketing, e-mail, e-mail marketing, newsletters, deliverability, email service, email service provider, esp, newsletter service
Donate link: https://circupress.com/
Requires at least: 3.5.0
Tested up to: 4.9.7
Stable tag: 2.51
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Send beautiful, responsive newsletters with your latest posts to subscribers without lifting a finger. We even widgetized the subscription form!

== Description ==

[CircuPress](http://www.circupress.com/?utm_source=plugin-readme&utm_medium=description&utm_campaign=1.0) is the only **email service provider** developed specifically for WordPress, designed and built by [Digital Home Info](http://www.digitalhomeinfo.com/) and [DK New Media](http://www.dknewmedia.com/). Manage subscribers and send compliant emails directly from your WordPress administrative panel. We send the emails from our mail servers to ensure you get reliable, fast and optimal delivery to your subscribers.

[vimeo http://vimeo.com/84545408]

CircuPress Email Marketing features

* Subscriber Management
* Email Editor
* Campaign Reporting
* Subscriber Import
* Bounce Management
* Click Tracking
* Sign-Up Widget
* Scheduled Daily Digest
* Scheduled Weekly Digest
* Advanced Template Access
* Helpdesk
* Email Support
* Deliverability

For more information, check out [CircuPress](http://www.circupress.com/?utm_source=plugin-readme&utm_medium=description&utm_campaign=1.0 "Email for WordPress")

== Installation ==
1. Search for CircuPress in the WordPress.org plugin directory and click install. Or, upload the files to your wp-content/circupress/ folder.
1. Visit wp-admin/plugins.php and activate the CircuPress plugin.
1. Head to /wp-admin/edit.php?post_type=email&page=circupress-account and enter your site’s registration key. You can purchase your registration key at CircuPress.com

== Frequently Asked Questions ==
View our full list of FAQs at [CircuPress](http://www.circupress.com/faqs/?utm_source=plugin-readme&utm_medium=description&utm_campaign=1.0 "CircuPress FAQs")

= What’s included in each CircuPress plan? =
All plans include the ability to send on demand, daily and weekly digests to your subscribers, subscriber management, bounce management, click tracking, campaign reporting and support.

Prices are dependent upon how many emails you will be sending on a monthly basis. Update-to-date pricing and features can always be found on the [CircuPress Pricing](http://www.circupress.com/pricing/?utm_source=plugin-readme&utm_medium=description&utm_campaign=1.0 "Email for WordPress") page.

= How many sites can I run CircuPress on? = 
A CircuPress subscription can be run on one or multiple sites utilizing your account key. If you wish to have different sending credentials (from email address and information), you will need to purchase additional account(s). If you have multiple sites but don’t mind them all coming from the same sender, you simply use the same credentials and API key throughout each site in the CircuPress settings.

= Does CircuPress work with WordPress 3.0 Multisite installs? = 
Yes, CircuPress supports Multisite installs. If you wish to have different sending credentials for each site (from email address and information), you will need to purchase additional account(s). If you have multiple sites but don’t mind them all coming from the same sender, you simply use the same credentials and API key throughout each site in the CircuPress settings.

== Screenshots ==
1. Emails that have been sent are listed just like posts, with your campaign metrics.
2. Send an On Demand email any time simply by writing and publishing your email.
3. Manage your subscribers, add, edit and import subscribers.
4. Manage your account and set your templates.
5. Utilize our CircuPress support page to see the latest product information and get started.
6. Customize your templates with a simple image header upload.
7. Customize your templates with an advanced editing tab where you have full control.
8. Preview your templates in real-time.

== Changelog ==
= 2.51 =
* Cleaned up the functionality that removes tags that will break the feed that pushed content into the email.
= 2.50 =
* Corrected add_thickbox and put it in an initialization function
* Corrected load_plugin_textdomain from deprecated method
* Corrected WP_Widget constructor from deprecated method
= 2.43 =
* Added argument to exclude Custom Post Type of Email from public searches.
= 2.42 =
* Updated some CircuPress resource links internal to the plugin.
= 2.41 =
* Corrected an issue with the WP ajax url location in the subscription form javascript.
= 2.40 = 
* Added an exception and notification if the CircuPress servers are unavailable
= 2.39 = 
* Updated templates with all filters applied and shortcodes.
= 2.38 = 
* Added thumbnail support (featured images) to the On Demand email.
* Updated templates with auto formatting and shortcodes. 
= 2.37 = 
* Updated the currently released templates to 2.3 to accommodate for shortcodes and auto formatting. 
= 2.36 = 
* Added shortcode support. You must apply any custom CSS utilized with your shortcodes in your email template, but in this case at least the shortcode will not display unrendered
= 2.35 = 
* Corrected a bug with wpautop on single emails that are designed through the editor to ensure proper formatting
= 2.34 = 
* Added %%SOCIAL%%, %%SOCIAL_LEFT%%, and %%SOCIAL_RIGHT%% support to the single template.
= 2.33 = 
* Added wpautop on single emails that are designed through the editor to ensure proper formatting
= 2.32 = 
* Added standard image classes to the email templates
= 2.31 = 
* Corrected an issue with the header image upload script for the editor
= 2.30 = 
* Corrected an issue with the 2.1 templates and updated the form and form CSS to a tableless, responsive layout
* Added meta tag in new template head to ensure noindex and nofollow by search engines
* Updated the support page to pull a feed from our site’s knowledge base and news
= 2.22 = 
* If you obtain a new API key, the old key is cached and will not validate. This updates the cache when the account settings are saved.
= 2.21 = 
* Corrected an error with the widget list_id code
= 2.20 =
* Corrected a missing email subject in the scheduled email template.
* Added the ability to remove templates. The latest templates will be renewed.
= 2.10 =
* Rebuilt the method to insert your social links into the template.
* Added the %%SOCIAL%% substitution string that needs to be enclosed in your table 
settings.
* Released an updated template that utilizes the social string
= 2.02 =
* Corrected an issue with the request for the daily template
= 2.01 =
* Corrected an issue with the social links not properly setup in the new templates
= 2.00 =
* Removed support tab and will be focused on support via the WordPress plugin forums and our site
* Added report div on subscribers page for future charting and reporting
* Added function to retrieve reports in the CircuPress API
* New Templates - Added new On Demand and Scheduled Template
* Made sure new templates include new loop fix (for daily and weekly)
* Changed API endpoint to https://app.circupress.com
* Added Setup Wizard in lightbox that is generated when required settings are not configured
* Corrected an issue where plugin was authenticating on every CircuPress admin page load
* Using WordPress Transient to cache result of authentication for 24 hours. This reduces the load on the server and prevents errors on the client server if there is an issue with the CircuPress servers
* Hid the list selection on the widget
* Removed Error on Account Settings page when checking API
* Added a tracking pixel in the Administration that passes the administrative page to our Google Analytics account so we can track usage and improve behavior, no information regarding your domain or account are passed.
= 1.21 =
* Updated include references that were causing init errors 
= 1.19 =
* Updated a bug with the new template selection option
= 1.18 =
* Updated the template downloads to alphabetical order
* Updated the On Demand template selection and removed the option for Do Not Send
* Filtered the template selection to the specific template type
* Corrected an issue with the header upload
* Updated the support and idea platform, the last one was confusing
* Added confirmation messages 
= 1.17 = 
* Added video to plugin page
= 1.16 = 
* Corrected an issue with the version commit
= 1.15 = 
* Corrected a script issue that was impacting other admin functions outside of the CircuPress functions
= 1.14 = 
* Corrected a PHP script tag that was breaking the plugin for many
= 1.13 =
* Corrected the issue with the auto submission of the widget form
* Alphabetized the template listing
* Corrected an issue where, if no header image was saved, the sidebar content could not be saved
* Corrected an unreported issue where the image path could be saved to blank.
= 1.12 = 
* Corrected an issue with the header image not updating the path on the Customize Tab on the Editor.
* Added an option to opt in your uploaded list to the daily or weekly subscription.
* Cleaned up some CSS within the administrative pages.
* Detected whether or not Yoast SEO Plugin was installed and recommended disabling the Email post type for XML Sitemaps.
* Corrected an encoding issue with the preview email.
* Corrected the templates with sidebars to properly merge.
= 1.11 =
* Made email grid with reporting data sortable, corrected viewing issue with subscriber widget.
= 1.10 =
* Updated the template and scheduling logic per WordPress feedback on the plugin
* Added support for videos in email. We replace Vimeo and YouTube videos with still images and play buttons overlaid by a service on CircuPress.
= 1.0 =
* Initial public release.

== Upgrade Notice ==
= 2.51 =
* Cleaned up the functionality that removes tags that will break the feed that pushed content into the email.
= 2.43 =
* Added argument to exclude Custom Post Type of Email from public searches.
= 2.42 =
* Updated some CircuPress resource links internal to the plugin.
= 2.41 =
* Corrected an issue with the WP ajax url location in the subscription form javascript.
= 2.40 = 
* Added an exception and notification if the CircuPress servers are unavailable
= 2.39 = 
* Updated templates with all filters applied and shortcodes.
= 2.38 = 
* Added thumbnail support (featured images) to the On Demand email.
* Updated templates with auto formatting and shortcodes.
= 2.37 = 
* Updated the currently released templates to 2.3 to accommodate for shortcodes and auto formatting. Please upgrade your templates.
= 2.36 = 
* Added shortcode support
= 2.35 = 
* Corrected a bug with wpautop on single emails that are designed through the editor to ensure proper formatting
= 2.34 = 
* Added %%SOCIAL%%, %%SOCIAL_LEFT%%, and %%SOCIAL_RIGHT%% support to the single template.
= 2.33 = 
* Added wpautop on single emails that are designed through the editor to ensure proper formatting
= 2.32 = 
* Added standard image classes to the email templates
= 2.31 = 
* Corrected an issue with the header image upload script for the editor
= 2.30 = 
* Corrected an issue with the 2.1 templates and updated the form and form CSS to a tableless, responsive layout
* Added meta tag in new template head to ensure noindex and nofollow by search engines
* Updated the support page to pull a feed from our site’s knowledge base and news
= 2.22 = 
* Corrected an issue with cached the cached validation of the API key
= 2.21 = 
* Corrected an error with the widget list_id code
= 2.20 =
* Updated scheduled template that corrects the email subject. Added the ability to remove templates.
= 2.10 =
* Update your template for a rewritten, dynamic social links section in your On Demand and Digest emails
= 2.02 =
* Corrects an issue for proper population of the daily digest
= 2.01 =
* Corrected an issue with the social links not properly setup in the new templates
= 2.00 =
* This upgrade is a major upgrade with new templates and a simpler user interface with more descriptions so that users can configure the plugin easier.
= 1.21 = 
* Corrected init error include references
= 1.17 = 
* Added video to plugin page. No need to upgrade.
= 1.16 = 
* Corrected an issue with the version commit
= 1.15 = 
* Corrected a script issue that was impacting other admin functions outside of the CircuPress functions
= 1.14 = 
* Corrected a PHP script tag that was breaking the plugin for many
= 1.13 =
* Corrected header image and sidebar issue.
* Corrected the issue with the auto submission of the widget form
= 1.12 =
* Corrected header image, template sidebar issue and various other minor cosmetic issues.
= 1.11 =
* Corrected Subscribe Widget
= 1.10 =
* Mandatory Update
= 1.0 =
* Initial public release.