=== Just A Tweet ===
Contributors: Aelora
Donate link: http://reliti.com/donate/
Tags: twitter, tweet
Requires at least: 2.7
Tested up to: 3.1
Stable tag: 0.1

Add a function to get the most recent Tweet from a feed

== Description ==

Adds a `just_a_tweet` function that allows you to display only the most recent
Tweet from a Twitter feed.

This came about because I wanted a way to display my most recent tweet in the 
header of my site. Looking through dozens of Twitter plugins I couldn't find
one that just got the most recent tweet without too much extraneous HTML and
also cached the request. This function does both.

For more info, visit <a href="http://reliti.com/just-a-tweet/">Reliti.com</a>

== Installation ==

1. Upload `just-a-tweet` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place `<?php just_a_tweet('username'); ?>` in your templates

The function `just_a_tweet` takes up to 4 parameters

$twitterUser - Required - The name of the Twitter user you want to request

$cacheAge - Optional - Number of minutes after which the cache is considered stale. Defaults to 5

$forceRefresh - Optional - If true then the cache is not used, although it is
still filled. Defaults to false

$echo - Optional - Whether the function should also echo out the HTML built. Either
way the HTML is returned. Defaults to true

== Frequently Asked Questions ==
None yet


== Changelog ==

= 0.1 =
* Initial Release

== Upgrade Notice ==

= 0.1 =
First release, nothing to upgrade