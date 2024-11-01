=== ULeak Security & Monitoring Plugin ===

Contributors: zephyrus1337
Company link: http://uleak.de
Tags: ULeak, malware monitoring, password security, cloud security, multi-website monitoring, hacked, availability monitoring, security monitoring
Stable tag: 4.4.2
Requires at least: 3.8
Tested up to: 4.4.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

ULeak is one of the best and most coherent cloud-based security scanner today. We aim to provide website owners the most concise security resource on the web and the best management tool for their projects.
This plugin searches the files on your website and the posts and comments tables of your database for anything suspicious. It also examines your list of active plugins for unusual filenames.
This plugin is a scanning application that does not remove anything. It is also just an additional feature beside ULeaks regular service as a website security provider - especially for WordPress users. 
Find more details in the "How does it work" section on http://www.uleak.de.

= Malware scan =

This plugin provides a malware scan to find all backdoor scripts and potential risks within your Wordpress installation. Log in to your ULeak API account to synchronize daily scanning results to your Uleak dashboard. You can find the daily synchronization process in the WordPress cron event scheduler. We also will send you an email alert if an infected file or leaked admin password was found.

= Leaked password compliance =

ULeak has a feature that will check all admin account passwords against our leaked password repository. This repository is created on a regular basis and consists of already cracked passwords only. These have been derived from public password-leaks and years of experience working with hashcat. Furthermore we actively scan for new password leaks and add them to the collection regularly.
Currently listed passwords: 194459270

= Cloud based result synchronization =

The plugin is scheduled to perform a daily transfer of your scanning results to your ULeak subscription.

= Security =

ULeak **protects your site** against malware, backdoor scripts, xss attacks, leaked passwords and brute-force attacks. Unauthorized logins and leaked passwords will be detected and banned. If you have a subscription we also monitor your sites for down-/uptime, responsetime, blacklists, potential risks and ssl hacks.

= Dedicated Support =

We have a team of engineers ready to help you. Ask your questions at ULeaks helpdesk (http://uleak.de/support).


== Installation ==

[Download ULeak from the official website](http://uleak.de/home/download/file_01). Alternatively you can install ULeak via the plugin directory or by uploading the files manually to your server. After activating the plugin an automatic update will be executed to hit the required Wordpress version.
A new menu item called "ULeak Security" will be available under the Tools menu.
If you need additional help contact the support staff at http://uleak.de/support.


== Frequently Asked Questions ==

= Is ULeak free? =
Yes! To use the core features of the plugin NO subscription is required. If you like to monitor numerous WordPress installations from one central dashboard get a subscription - find more details here (http://uleak.de/pricing).

= Can I get a free trial subscription? =
If you wish to trial the service simply sign up and if you are not happy with the results you can get a money back refund within 5 days of purchase.

= Is the payment for a recurring subscription? =
No. You are not locked into any subscription. The Beginner, Pro and Expert membership lasts for 12 months and will expire if you do not chose to renew. A reminder email will be sent 14 days before expiration.

= How does the payment system work? =
Payment is via Credit Card or PayPal. There are no lock in contracts or subscriptions. Once payment is made you will be directed to a signup page where you enter your primary email - it will be used for the login and delivery of your scan results.

= Can I upgrade or change plans? =
Yes. Once you subscribed we offer various upgrade options. If you do not find the upgrade you are looking for please submit a ticket and ULeaks support team will help.

= Are there any additional taxes or fees? =
There are no extra fees, no additional taxes and no hidden costs. The price you see is the price that you pay. All of ULeaks prices are listed in USD and the conversion will be handled by Paypal automatically.

= Will the WordPress plugin remove malware from my website? =
The ULeak Scanner Plugin for wordpress will audit and detect malware using a remote scanner. It does not remove malware but it does offer a path to the payload when available. Also it will offer additional recommendations to help you getting your website cleaned.

= Do I have to do anything to activate the ULeak plugin? =
Simply install and activate the plugin. An automatic update will be created individually - highly compatible to your wordpress version. ULeaks plugin works as a paid service and you have to register a membership subscription to activate the plugin. This is done by using an API key from your ULeak dashboard.

= Do the WordPress plugins work with numerous WordPress installations? =
Yes! This means that all the sites will share the scanning results and leaked password information to your private ULeak cloud.

= How often are new features added? =
Because of compatibility reasons and feature enhancements ULeaks extensions are maintained and updated regularly. You can subscribe to receive notifications for updates from the offical wordpress plugin repository (svn) or from github.

= Interpreting the Results =
It is possible that the scanner will find false positives (i.e. files which do not contain malicious code). If you are unsure feel welcome to contact the support team (http://uleak.de/support/),
You should be most concerned if the scanner is:
* making matches around unknown external links
* finding base64 encoded text in modified core files or the `wp-config.php` file;
* listing extra admin accounts
* or finding content in posts which you did not put there.


== Screenshots ==

See https://www.uleak.de


== Upgrade Notice ==
Version 1.1
Version 1.2
Version 1.2.1
Version 1.2.2
Version 1.2.3

== Changelog ==
= 1.0 =
First Beta Version
= 1.1 =
Added ULeak SECURE Seal
Release date: May 1th, 2016
= 1.2 =
Import of vulnerability scan
Public access to services without subscriptions
Free features and password compliance API
= 1.2.1 =
Quickfix array syntax
= 1.2.2 =
WP-Account Overview
= 1.2.3 =
ULeak Secure Seal width fixed