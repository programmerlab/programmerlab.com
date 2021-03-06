=== Post Star Rating ===
Contributors: O Doutor, bestweblayout
Tags: rating, voting, post, stars, rate, rate post, reit, rait, raite, reite, post star rating, post star rating plugin, reting, reiting, raiting, best posts, best posts of month, posts limit, voting stars, trends, bests of current month.
Requires at least: 3.3
Tested up to: 4.0.1
Stable tag: 0.3.5
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Post Star Rating is a plugin that allows blog users to rate posts in a classic five stars way.

== Description ==

Allows users to vote for the posts and display ranking of the best posts.

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload `post-star-rating.zip` to the '/wp-content/plugins/' directory
2. Unzip the post-star-rating.zip to the '/wp-content/plugins/better-delete-revision/' directory
3. Activate the plugin through the 'Plugins' menu in WordPress
4. Add the if( function_exists( 'psr_show_voting_stars' ) ) psr_show_voting_stars(); code in your template files. For example: put this after the post title: <?php if( function_exists( 'psr_show_voting_stars' ) ) psr_show_voting_stars(); ?>

== Extra shortcodes ==

If you want to have scoreboards displayed on your website, you can use the following shortcodes:

- [psr_bests_of_month]: Displays a list with 10 best post of the current month.
- [psr_bests_of_month month=8]: Displays a list with 10 best posts of august. You can specify month number from 1 to 12.
- [psr_bests_of_month month=8 limit=5]: Displays a list of 5 best posts of august. You can specify both month number from 1 to 12 and any digits for the limit.
- [psr_bests_of_moment]: Displays a list with the 10 best post at the moment. It shows trends too.
- [psr_bests_of_moment limit=5]: Displays a list with the "limit" of the best post at the moment. You can specify any digits for the limit. It shows trends too.

== Screenshots ==

1. Stars for rating.
2. Stars after voting.
3. [psr_bests_of_month] and [psr_bests_of_moment] shortcodes output.

== Changelog ==

= Version 0.3.5 - 03.12.2014 =
* Update : We remove a menu page.

= Version 0.3.4 =
* Update : We updated all functionality for Wordpress 4.0.1.
* NEW    : We added a menu page.

= Version 0.3.3 =
* NEW: We updated all functionality for Wordpress 4.0.
* NEW: We added extra shortcodes: [psr_bests_of_month] and [psr_bests_of_moment].

= Version 0.3.2 =
* Bugfix: Fix PRS_bests_of_moment($limit) to show up to $limit rows.

= Version 0.3.1 =
* Bugfix: Avoid database error in PSR_bests_of_moment() Tag when rating database is empty.

= Version 0.3 =
* New: AJAX support for voting without page reloads.
* New: Added Template Tag "PSR_bests_of_moment($limit)".
* Bugfix: Don't allow rating if cookies are disabled.
* Bugfix: The entries of list generated by "PSR_bests_of_month($month, $limit)" tag are links to the posts now.
* Bugfix: CSS adjusts.

= Version 0.2 =
* New: Added two fields to database: "ip" and "vote_date".
* New: Added Template Tag "PSR_bests_of_month($month, $limit)".

= Version 0.1.2 =
* Bugfix: Avoid Internet bots and spiders like GoogleBot to follow rating links.

= Version 0.1.1 =
* Bugfix: Headers already sent: Changed setcookie to Init method.
* Bugfix: Image URL in CSS styles.
* Bugfix: Image background no-repeat.
* Bugfix: Error message in install.php script.
* Bugfix: Internal documentation.

= Version 0.1 =
* New: Initial version

== Upgrade Notice ==

= Version 0.3.5 =
We remove a menu page.

= Version 0.3.4 =
We updated all functionality for Wordpress 4.0.1. We added a menu page.

= Version 0.3.3 =
We updated all functionality for Wordpress 4.0. We added extra shortcodes: [psr_bests_of_month] and [psr_bests_of_moment].

= Version 0.3.2 =
Fix PRS_bests_of_moment($limit) to show up to $limit rows.

= Version 0.3.1 =
Avoid database error in PSR_bests_of_moment() Tag when rating database is empty.

= Version 0.3 =
AJAX support for voting without page reloads Added Template Tag "PSR_bests_of_moment($limit)". Don't allow rating if cookies are disabled. The entries of list generated by "PSR_bests_of_month($month, $limit)" tag are links to the posts now. CSS adjusts.

= Version 0.2 =
Added two fields to database: "ip" and "vote_date". Added Template Tag "PSR_bests_of_month($month, $limit)".

= Version 0.1.2 =
Avoid Internet bots and spiders like GoogleBot to follow rating links.

= Version 0.1.1 =
Headers already sent: Changed setcookie to Init method. Image URL in CSS styles. Image background no-repeat. Error message in install.php script. Internal documentation.

= Version 0.1 =
Initial version.
