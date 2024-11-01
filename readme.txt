=== Statistics ===
Contributors: Joshoua Miller
Tags: stat, stats, track, tracking, plugin, analytics, visitor, visit, Stats, views, post, page, counter, visiotors, 
Donate link: http://wpreviewed.weebly.com
Requires at least: 2.9
Tested up to: 3.8
Stable tag: 1.7

Advanced Real time Web Stats for your Wordpress Blog/Website
.
== Description ==

Advanced Real time Web Stats for your Wordpress Blog/Website.

Count every viewer and every article pageview for each blog entry, doesn't matter how and where it is: Stats tracks views of each blog post or page, not only on a single article but also on other page where the complete article is shown, i.e. blog front page, category pages, search result page, archive pages and even RSS feeds.

Most statistic tools count visitors and page impressions per actual page or website url, i.e. an article view is only counted, when your visitor clicks on the article's permalink. This doesn't make sense for blogs, because many of your visitors read articles on your blog's front page or in full content RSS feeds.
This plugin does not supply endless features to analyze visitor behavior, it just gives you an accurate impression, which of your articles is viewed how many times.

Count every view just once: Stats can distinguish between recurring and non-recurring page views per (anonymous) user to compute a unique or total view count per post/page.

Show off your stats: You can display view count for each article on your blog.

Analyze Stats: Stats offers comfortable analyzation tools, including graphs, dashboard widget etc.

*7 Great Reasons To Use This Plugin*

1. Count viewers and article views for each post and article using tracking pixel
2. Tracking pixel is displayed automatically, no theme customization needed.
3. Define where views are tracked (home page, single page, archive pages, RSS feeds)
4. Define if logged in users should be tracked.
5. Identify recurring users per pseudonym, stored in user browser as a cookie.
6. View stats in Wordpress backend. Top 10 articles, based on unique or total page views, bar chart for Top Articles (including unique and total views), line chart with the daily totals of unique article views, total article views and unique viewers.
7. Dashboard widget with quick overview chart

See more at http://wpreviewed.weebly.com


== Installation ==

1. Download Stats
1. Upload `stats-wp/` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

To show off your Stats add the following short code to your Wordpress Template code:

* Unique views: `<?php print(get_analytic()); ?>`
* Total views: `<?php print(get_analytic(false)); ?>`

After an update, please deactivate and activate the plugin to make sure all database settings are up to date.

