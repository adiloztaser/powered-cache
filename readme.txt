=== Powered Cache – Caching and Optimization for WordPress – Easily Improve PageSpeed & Web Vitals Score ===
Contributors:  poweredcache, skopco, m_uysl
Tags: cache, caching, web vitals, performance, fastest, page speed, optimization, cdn, object cache, minify, powered cache
Requires at least:  5.1
Tested up to:  6.0
Stable tag:  2.2.1
License: GPLv2 (or later)
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Donate link: https://poweredcache.com/donate/
Requires PHP: 5.6

The most powerful caching and performance suite for WordPress. Easily Improve PageSpeed & Web Vitals Score.

== Description ==

Powered Cache is a comprehensive caching and optimization plugin for WordPress. It's easy to use and dramatically boosts site performance in a few clicks.

Powered Cache Free contains everything that you need to optimize your website performance, and the [Powered Cache Premium](https://poweredcache.com) plugin and its extensions unlock even more tools and functionality.

= Features ⚡️ =

__Simple and easily configurable__: You can import and export settings with a single click.

__Page Caching__: Lightning-fast pages. (Trusted by enterprise-grade websites)

__Object Caching__: Speed up dynamic pageviews. It supports Redis, Memcached, Memcache, and APCu.

__Page Cache Rule Management__: Need advanced caching configurations? Got it covered under advanced options. [Details](https://docs.poweredcache.com/advanced-options/)

__File Optimization__: Easily minify and combine CSS, JS files.

__Database Optimization__: Keep redundant data away from your database.

__Media Optimization__: Enable Lazy Load, control WordPress embeds, remove emoji scripts.

__Combine Google Fonts__: Combine Google Fonts URLs into a single URL and optimize the font loading.

__Rewrite Support__: Automatic .htaccess configuration for the ideal setup. The cached file can be served without executing PHP at all.

__Mobile Support__: Separate cache file for mobile, in case want to use the separate theme for the mobile.

__Logged-in User Cache__: If you have user-specific content or running a membership site, it creates cached results for the logged-in users.

__CDN Integration__: Integrate your website with CDN; you just need to enter CNAME(s) and corresponding zones.

__Cache Preloading__: Creating cached pages in advance. This feature will keep caching layer warm.

__Prefetched DNS__: Resolve domain names before resources get requested. Reduce DNS lookup time.

__Gzip Support__: Compress caching files with gzip.

__Built-in Extensions__: Cloudflare, Heartbeat

__Multisite Support__: You can activate network-wide or site basis. It's compatible with domain mapping.

__Smart Cache Purging__: Only purge the cache that is affected by the content changes.

__Compatible__: Tested and compatible with popular plugins.

__Battle Tested__: Trusted by enterprise-grade websites.


= Built-in Extensions =
Built-in extensions (aka add-ons) shipped with Powered Cache to provide more functionality.

__Cloudflare__: Cloudflare compatibility and functionalities ***Free***
__Heartbeat__: Manage the frequency of the WordPress Heartbeat API. ***Free***
__Varnish__: Varnish cache purging ***Premium only***
__Google Tracking__: Powered Cache will host Google scripts on your server to help satisfy the PageSpeed recommendation. ***Premium only***
__Facebook Tracking__: Powered Cache will host Facebook scripts on your server to help satisfy the PageSpeed recommendation. ***Premium only***

= Premium Features =
Here is a list of the amazing features included in Powered Cache Premium:

- Critical CSS & Load CSS Asynchronously.
- Image Optimizer. On the fly Image Compression and WebP conversion.
- Sitemap Preloading.
- Scheduled Database cleanups.
- Varnish extension.
- Google tracking extension.
- Facebook tracking extension.
- WP-CLI commands are ready to save your time.
- Top-notch premium support.
- No Ads on the plugin page.

By upgrading to Powered Cache Premium you also get access to one-on-one help from our knowledgeable support team and our extensive documentation site.

**[Learn more about Powered Cache Premium](https://poweredcache.com/)**

= Contributing & Bug Report =
Bug reports and pull requests are welcome on [Github](https://github.com/poweredcache/powered-cache). Some of our features are premium only, please consider before sending PR.

= Documentation =

__Documentation site__: [https://docs.poweredcache.com/](https://docs.poweredcache.com/)

__Developer Docs__: [https://poweredcache.github.io/docs/](https://poweredcache.github.io/docs/)  (***Hook referance***)


== Installation ==

=== From within WordPress ===
1. Visit 'Plugins > Add New'
2. Search for 'Powered Cache'
3. Activate Powered Cache from your Plugins page.
4. That's all.

=== Manually ===
1. Upload the `powered-cache` folder to the `/wp-content/plugins/` directory
2. Activate the Powered Cache plugin through the 'Plugins' menu in WordPress
3. That's all.

== Frequently Asked Questions ==

= How do I know my site is being cached? =
The easiest way is to make sure your site is being cached. Open your site in incognito mode of your browser and right-click on the page. If you see `<!-- Cache served by PoweredCache -->` information that means you are getting a cached result.

= Is it compatible with multisite? =
Yes, it's 100% compatible with multisite. You can activate it on the network-wide or per-site basis.

= Is it compatible with domain mapping? =
Yes, it's compatible with Mercator and native domain mapping feature with WordPress core.

= What is the built-in extension? =
We designed Powered Cache is a complete optimization solution for WordPress. However, we believe that your system should be tailored to your needs without the added weight of unwanted functionality. We strive to perfect this balance with our built-in extensions.

= What about mobile caching? =
We support mobile devices and user agents, if your template is not responsive you can use mobile caching with a separate file. It all works.

= How to get premium version of plugin? =
You can buy from [poweredcache.com](https://poweredcache.com/)

= Is it compatible with Cloudflare? =
Yes, you just need to enable Cloudflare extension.

= Is it compatible with Jetpack? =
Yes, we don't get any problems with Jetpack.

= Is it compatible with WPML? =
Yes, it's compatible with [WPML](https://wpml.org/).


= Is it compatible with ecommerce plugins? =
Yes, you can use with WooCommerce, Easy Digital Downloads and BigCommerce. If you are using any other eCommerce plugin, just make sure dynamic pages are excluded from the cache.

= How can I disable caching for a particular page? =
You can disable caching from the meta box in the post editing page or enter pages in the "Never cache the following pages" under the "Advanced Options" section.

= Can I export/import settings? =
Yes, you can find export/import options in the "Misc" sections of the settings page.

= Does it cache API requests? =
Yes, it caches GET requests on API. If you have query parameters on the request, you will need to allow query parameter in the"Accepted query strings" under the "Advanced Options" section.

= Is it compatible with PHP 8+ =
Yes, it’s compatible with PHP 8+


== Screenshots ==
1. Basic Options
2. Advanced Options
3. File Optimization
4. Media Optimization
5. CDN Integration
6. Preload Options
7. Database Optimization
8. Extensions


== Changelog ==

= 2.2.1 (April 26, 2022) =
- File Optimizer CDN integration fix.

= 2.2 (April 25, 2022) =
- Added: Image optimizer.
- Added: Swap Google Fonts.
- Added: Cache miss reason.
- Added: Preconnect resource hint.
- Improvements: CDN module (refactored).
- Improvements: Lazy Load (modernized).
- Fix: Windows compatibility issues.
- Fix: Transients clean-up from DB when object cache in place.
- New filter: `powered_cache_fo_disable` to control file optimizer.
- New filter: `powered_cache_is_local_site`.
- New filter: `powered_cache_cdn_extensions`.
- New filter: `powered_cache_preconnect_resource`.
- New compat: Cornerstone builder.
- Tested: WordPress 6.0

= 2.1.2 (March 28, 2022) =
- Fix: Lazy Load issue.

= 2.1.1 (March 15, 2022) =
- Added a new compat: Cookies and Content Security Policy plugin.
- Change post pecific cache control capability. (`edit_posts` to `edit_others_posts`)
- Fixed: Make sure cdn_hostname and cdn_zone have index 0 for placeholder.
- Fixed: normalize vary cookie value.

= 2.1 (March 14,2022) =
- Added: Critical CSS Settings.
- Added: Post specific file optimization options.
- Added: Jetpack boost compatibility
- Improvements: Settings page UI on mobile.
- Improvements: CDN Integration.
- Improvements: Cache Preloading.
- Fixed: Google fonts combine.
- Fixed: CSS minification should work when the group contains a single file.
- Fixed: CDN integration warnings.
- Added: Automatic CORS configuration for .htaccess and nginx.
- Bumped minimum WP requirement to 5.1

= 2.0.4 =
- Tested with WP 5.9
- UI Update
- Fix a potential notice about the user agent

= 2.0.3 =
- Small UI updates
- Fix: metabox registration on the screens other than post

= 2.0.2 =
- Hotfix: don't break block editor on reusable blocks

= 2.0.1 =
- Fix: Smart cache purge on post update.
- Localization improvements: Set script localization correctly.
- Improved WPML compatibility.
- Added `.htaccess` execution rule for file optimizer.

Detailed changelog located in [changelog page](https://poweredcache.com/changelog)

== Upgrade notice ==

= 2.0 =
 - Requirements have been updated.
 - Includes some breaking changes. If you have been using the plugin functions or hooks, consider testing it before the upgrade.


= 1.2 =
 - Default `WP_CACHE_KEY_SALT` has been changed, be careful about upgrading

If you get unexpected results after upgrade or migrating to new hosting, please check WordPress drop-in caching files which are located in `wp-content/advanced-cache.php` and `wp-content/object-cache.php`
