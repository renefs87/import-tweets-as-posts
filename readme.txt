=== Import Tweets as Posts ===
Contributors: Chandan Kumar
Plugin Name:  Import Tweets as Posts
Plugin URI:   http://plugins.svn.wordpress.org/import-tweets-as-posts/
Author URI:   http://www.chandankumar.in
Author:       Chandan Kumar
Donate link:  http://chandankumar.in
Tags: Import tweets as posts, tweets to posts, twitter feeds, posts, import tweets, import tweets to blog, import tweets by search query
Requires at least: 2.8.6
Tested up to: 3.9.2
Stable tag: 1.5
License: GPLv2

== Description ==

"Import Tweets as Posts" allows to easily import tweets (from user's timeline or by using search query) as Posts in WordPress. User can specify the import interval time, Category, Post Title. There is also an option to exclude retweets and replies from user's twitter timeline.

Released under the terms of the GNU GPL, version 2.
http://www.fsf.org/licensing/licenses/gpl.html

NO WARRANTY.
Copyright (c) 2014 Chandan Kumar


== Installation ==

1. Extract the import-tweets-as-posts/ folder file to /wp-content/plugins/

2. Activate the plugin at your blog's Admin -> Plugins screen

3. Go to Plugin Settings from "settings -> Import Tweets as Posts"

4. Enter Twitter OAuth Keys (consumer key, consumer secret, access token, access token secret) in plugin settings fields (See FAQs or <a href="http://www.chandankumar.in/how-to-create-twitter-application-and-generate-oauth-authentication-keys/" target="_blank" title="How to Create Twitter Application and Generate OAuth Authentication Keys">post</a>)

6. Also make the following fields settings as per your requirements:
<ul>
  <li>Import Tweets From ('User Timeline', 'Search Query')</li>
  <li>Enter 'Twitter Id' or 'Search String' as per above selection.</li>
  <li>If selected 'Search Query', set 'Twitter Search Result Type' from dropdown.</li>
  <li>Tweets Post Title (Leave this blank if you want to display tweet text as title)</li>
  <li>No. of Tweets to Import</li>
  <li>Tweets Imports Time Interval (e.g. Enter "1" for 1 minute interval)</li>
  <li>Assigned Category to Twitter Posts</li>
  <li>Twitter Posts Default Status</li>
  <li>Import Retweets</li>
  <li>Exclude Replies</li>
</ul>

Note: All fields are required to work this plugin more efficiently.


== Upgrade Notice ==

= There is a new version of Import Tweets as Posts available. View version 1.5 update now. =


== Screenshots ==
...


== Changelog ==

= 1.5 =
<ul>
<li>Added option to set tweet publish date as per WordPress timezone.</li>
<li>Hyperlinked the mentioned user under Tweets.</li>
<li>Fixed Issue: Each tweet was creating an empty WordPress media object in the media library.</li>
<li>Fixed Issue: Twitter's t.co links were not being converted to hyperlinks just because of https.</li>
</ul>

= 1.4 =
<ul>
<li>Now user can exclude replies from tweets.</li>
<li>Added search query option to import tweets. Now user have two options to import tweets either through search query or user timeline.</li>
</ul>

= 1.3 =
<ul>
<li>Hyperlinked the hash tags.</li>
<li>Additional Fix: Tweet will not be imported again, if it is there in posts with any of these post status:
'publish', 'pending', 'draft', 'auto-draft', 'future', 'private', 'inherit'</li>
</ul>

= 1.2 =
<ul>
<li>New version will set imported tweet's image as featured image in post.</li>
<li>It also allows you to set tweet text as post title.</li>
</ul>

= 1.1 =
<ul>
<li>Bug has been fixed for re-tweets import option</li>
</ul>



== Frequently Asked Questions ==

= How do I get Twitter OAuth keys? =
To create your Twitter OAuth API Keys for the first time, just go through the steps:
<ol>
<li>Go to https://dev.twitter.com/apps/new and log in, if necessary</li>
<li>Supply the necessary required fields, accept the TOS, and solve the CAPTCHA.</li>
<li>Submit the form</li>
<li>Copy the consumer key and consumer secret from the screen into your application</li>
<li>Ensure that your application is configured correctly with the permission level you need (read-only, read-write, read-write-with-direct messages).</li>
<li>On the application's detail page, invoke the "Your access token" feature to automatically negotiate the access token at the permission level you need.</li>
<li>Copy the indicated access token and access token secret from the screen into your application. Be sure and configure your application as needed before attempting the "your access token" step.</li>
</ol>

= Can I schedule twitter feed check/import interval time? =
Yes, you can specify the schedule time in field called "Tweets Imports Time Interval" under plugin settings.

= Send your queries =
http://chandankumar.in
