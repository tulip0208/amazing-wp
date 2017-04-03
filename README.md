# awesome-wp-speed-up
Plugins and resources to speed up and optimize your WordPress site

## Table Of Contents
* [Page Caching Plugins](#page-caching-plugins)
* [Object Caching Plugins](#object-caching-plugins)
* [Minification Plugins](#minification-plugins)
* [CDN Integration Plugins](#cdn-integration-plugins)
* [Image Optimization Plugins](#image-optimization-plugins)
* [Lazy Loading Plugins](#lazy-loading-plugins)
* [Reduce HTTP Requests on Load Plugins](#reduce-http-requests-on-load-plugins)
* [Database Optimization Plugins](#database-optimization-plugins)
* [Slow Query and Debugging Plugins](#slow-query-and-debugging-plugins)
* [NGNIX and Varnish Control Plugins](#ngnix-and-varnish-control-plugins)
* [Performance Benchmarking Sites](#performance-benchmarking-sites)
* [Further Reading](#further-reading)

## Page Caching Plugins
* [WP Fastest Cache](https://wordpress.org/plugins/wp-fastest-cache/) - This plugin creates static html files from your dynamic WordPress blog.
* [WP Super Cache](https://wordpress.org/plugins/wp-super-cache/) - This plugin generates static html files from your dynamic WordPress blog. After a html file is generated your webserver will serve that file instead of processing the comparatively heavier and more expensive WordPress PHP scripts.
* [Comet Cache](https://wordpress.org/plugins/comet-cache/) - If you care about the speed of your site, Comet Cache is one of those plugins that you absolutely MUST have installed Comet Cache takes a real-time snapshot (building a cache) of every Page, Post, Category, Link, etc. 
* [Cache Enabler](https://wordpress.org/plugins/cache-enabler/) - The Cache Enabler plugin creates static HTML files and stores them on the servers disk.
* [Simple Cache](https://wordpress.org/plugins/simple-cache/) - Simple Cache was constructed after getting frustrated with the major caching plugins available and building sites with developer-only complex caching solutions that get millions of page views per day.
* [Gator Cache](https://wordpress.org/plugins/gator-cache/) - Gator Cache is an easy to manage page cache for WordPress. Once installed, it automatically updates new and updated content in your cache.
* [Vendi Cache](https://wordpress.org/plugins/vendi-cache/) - Vendi Cache takes your slow database-driven pages and turns them into very fast static HTML files.
* [SG Optimizer](https://wordpress.org/plugins/sg-cachepress/) - This plugin is designed to link WordPress with the SiteGround Performance services.
* [Vendi Cache](https://wordpress.org/plugins/vendi-cache/) - Vendi Cache takes your slow database-driven pages and turns them into very fast static HTML files.
* [WP Rocket](https://wp-rocket.me/) - Your website at lightspeed.
* [W3 Total Cache Fixed](https://github.com/szepeviktor/w3-total-cache-fixed) - A community driven build of W3 Total Cache. The aim is to continuously incorporate fixes, improvements, and enhancements over the official WordPress release of W3 Total Cache.
* [WP-FFPC](https://wordpress.org/plugins/wp-ffpc/) - WP-FFPC is a cache plugin for WordPress.
* [Cachify](https://wordpress.org/plugins/cachify/) - Cachify optimizes your page loads by caching posts, pages and custom post types as static content.

## Object Caching Plugins
* [WP Redis](https://wordpress.org/plugins/wp-redis/) - For sites concerned with high traffic, speed for logged-in users, or dynamic pageloads, a high-speed and persistent object cache is a must. 
* [Memcached Redux](https://wordpress.org/plugins/memcached-redux/) - Changes the famous Memcached WP Object Cache backend to actually use the Memcached class (not the Memcache class).
* [APCu Object Cache Backend](https://wordpress.org/plugins/apcu/) - Using this Plugin WordPress is able to store certain regular used elements into a persistent cache.

## Minification Plugins
* [Autoptimize](https://wordpress.org/plugins/autoptimize/) - Autoptimize makes optimizing your site really easy. It concatenates all scripts and styles, minifies and compresses them, adds expires headers, caches them, and moves styles to the page head and can move scripts to the footer.
* [WP Roids](https://wordpress.org/plugins/wp-roids/) - Fast AF caching! Plus minifies your site’s HTML, CSS & Javascript.

## CDN Integration Plugins
* [CDN Enabler](https://wordpress.org/plugins/cdn-enabler/) - A content delivery network (CDN) is a network of distributed edge servers, which accelerate your content around the globe. The main benefits of a CDN are scalability, reliability and performance.
* [Cloudflare](https://wordpress.org/plugins/cloudflare/) - The easiest way to setup Cloudflare for your WordPress site.
* [DreamSpeed CDN](https://wordpress.org/plugins/dreamspeed-cdn/) - This plugin will automatically copy images, videos, documents, and any other media added through WordPress’ media uploader to DreamSpeed.
* [Full Site Cache for KeyCDN](https://wordpress.org/plugins/full-site-cache-kc/) - This plugin can help you to use KeyCDN on your WordPress, not only your Media and CSS, but also all HTML page.
* [Full Site Cache for CloudFront](https://wordpress.org/plugins/full-site-cache-cf/) - If you blog are using CloudFront on the main WordPress domain and you want to cache HTML page for not logged in user.
* [Cloudinary](https://wordpress.org/plugins/cloudinary-image-management-and-manipulation-in-the-cloud-cdn/) - With Cloudinary, all your images are automatically uploaded, normalized, optimized and backed-up in the cloud instead of being hosted on your servers.
* [Photon](https://jetpack.com/support/photon/) - Photon is an image acceleration and editing service for sites hosted on WordPress.com or on Jetpack-connected WordPress sites. That means less load on your host and faster images for your readers.

## Image Optimization Plugins
* [EWWW Image Optimizer](https://wordpress.org/plugins/ewww-image-optimizer/) - The EWWW Image Optimizer is a WordPress plugin that will automatically optimize your images as you upload them to your blog.
* [EWWW Image Optimizer Cloud](https://wordpress.org/plugins/ewww-image-optimizer-cloud/) - The EWWW Image Optimizer is a WordPress plugin that will automatically optimize your images as you upload them to your blog.
* [TinyPNG](https://wordpress.org/plugins/tiny-compress-images/) - Make your website faster by optimizing your JPEG and PNG images. This plugin automatically optimizes all your images by integrating with the popular image compression services TinyJPG and TinyPNG.
* [Imagify](https://wordpress.org/plugins/imagify/) - Speed up your website with lighter images without losing quality.
* [ImageRecycle](https://wordpress.org/plugins/imagerecycle-pdf-image-compression/) - ImageRecycle is an automatic Image and PDF content optimizer for WordPress website.
* [ShortPixel Image Optimizer](https://wordpress.org/plugins/shortpixel-image-optimiser/) - Increase your website’s SEO ranking, number of visitors and ultimately your sales by optimizing any image or PDF document on your website.
* [Kraken.io](https://wordpress.org/plugins/kraken-image-optimizer/) - This plugin allows you to optimize and resize new and existing WordPress image uploads through Kraken.io Image Optimizer’s API.
* [Optimus](https://wordpress.org/plugins/optimus/) - Optimus reduces the file size of uploaded media files automatically. Depending on the image and format, reductions in size of up to 70% are possible.

## Lazy Loading Plugins
* [Rocket Lazy Load](https://wordpress.org/plugins/rocket-lazy-load/) - Lazy Load displays images on a page only when they are visible to the user. This reduces the number of HTTP requests mechanism and improves the loading time.
* [Lazy Load](https://wordpress.org/plugins/lazy-load/) - Lazy Load displays images on a page only when they are visible to the user. This reduces the number of HTTP requests mechanism and improves the loading time.
* [Lazy Load XT](https://wordpress.org/plugins/lazy-load-xt/) - Lazy load images, YouTube and Vimeo videos, and iframes using Lazy Load XT.
* [Lazy Load for Videos](https://wordpress.org/plugins/lazy-load-for-videos/) - This plugin improves page load times and increases your Google PageSpeed Score. It replaces embedded Youtube and Vimeo videos with a clickable preview image.
* [Disqus Conditional](https://wordpress.org/plugins/disqus-conditional-load/) - DCL is an advanced version of Disqus Commenting System, with which experience the boosted page loading speed difference. 
* [Lazy Facebook Comments](https://wordpress.org/plugins/lazy-facebook-comments/) - Use Facebook comments system in your website without slowing down your website. 
* [Lazy Load for Comments](https://wordpress.org/plugins/lazy-load-for-comments/) - Lazy load WordPress default commenting system without any complex configurations. 

## Reduce HTTP Requests on Load Plugins
* [Heartbeat Control](https://wordpress.org/plugins/heartbeat-control/) - Allows you to easily manage the frequency of the WordPress heartbeat API with just a few dropdowns.
* [Disable Emoji](https://wordpress.org/plugins/disable-emojis/) - This plugin disables the new WordPress emoji functionality.
* [Disable Embeds](https://wordpress.org/plugins/disable-embeds/) - Disable Embeds
* [Disable Custom CSS](https://wordpress.org/plugins/disable-custom-css/) - This plugin automatically disables frontend database query for Custom CSS and Customizer section for setting Custom CSS, without need to manually choose any setting or option.
* [WP Disable](https://wordpress.org/plugins/wp-disable/) - Reduce HTTP requests - Disable Emojis, Disable Gravatars, Disable Embeds and Remove Querystrings. Added support to disable pingbacks, disable trackbacks, close comments after 28 days, Added the ability to force pagingation after 20 posts, Disable WooCommerce scripts and CSS on non WooCommerce Pages, Disable RSS, Disable XML-RPC, Disable Autosave, Remove Windows Live Writer tag, Remove Shortlink Tag, Remove WP API from header

## Database Optimization Plugins
* [WP-Optimize](https://wordpress.org/plugins/wp-optimize/) - WP-Optimize is an effective tool for automatically cleaning your WordPress database so that it runs at maximum efficiency.
* [WP-Sweep](https://wordpress.org/plugins/wp-sweep/) - WP-Sweep allows you to clean up unused, orphaned and duplicated data in your WordPress. It also optimizes your database tables.

## Slow Query and Debugging Plugins
* [Query Monitor](https://wordpress.org/plugins/query-monitor/) - Query Monitor is a debugging plugin for anyone developing with WordPress.
* [Debug Bar](https://wordpress.org/plugins/debug-bar/) - Adds a debug menu to the admin bar that shows query, cache, and other helpful debugging information.

## NGNIX and Varnish Control Plugins
* [Ngnix Helper](https://wordpress.org/plugins/nginx-helper/) - Add greater control for purging NGNIX cache if using for page caching.
* [Varnish HTTP Purge](https://wordpress.org/plugins/varnish-http-purge/) - Varnish HTTP Purge sends a PURGE request to the URL of a page or post every time it it modified.
* [WP Super Cache nginx.conf example](https://github.com/vstoykovbg/nginx.conf-examples/blob/master/wp-super-cache-nginx.conf.md) - Example configuration for Nginx and WordPress with WP Super Cache plugin.
* [Rocket-Nginx](https://github.com/maximejobin/rocket-nginx) - Rocket-Nginx is a Nginx configuration for the WordPress cache plugin WP-Rocket.

## Performance Benchmarking Sites
* [WebPageTest](https://www.webpagetest.org/) - Run a free website speed test from multiple locations around the globe using real browsers (IE and Chrome) and at real consumer connection speeds. You can run simple tests or perform advanced testing including multi-step transactions, video capture, content blocking and much more.
* [KeyCDN Site Speed Test](https://tools.keycdn.com/speed) - A page speed test that includes a waterfall breakdown and the website preview. Select any of the 14 test locations.
* [KeyCDN Performance Test](https://tools.keycdn.com/performance) - A free online web performance test. Query a single asset from 14 test locations.
* [Sucuri Load Time Tester](https://performance.sucuri.net/) - How fast is your site? You can test here the performance of any of your sites from across the globe.
* [GTmetrix](https://gtmetrix.com/) - Start optimizing your site! GTmetrix provides explanations for each recommendation, and gives you actionable advice.
* [Pingdom](https://tools.pingdom.com/) - Enter a URL to test the load time of that page, analyze it and find bottlenecks.

## Further Reading
* [WordPress Performance – Breaking It Down by HTTP Requests](https://www.keycdn.com/blog/wordpress-performance/) - WordPress can be a tricky beast as they say when it comes to web performance. Especially if you are comparing it against others running static sites.
* [Cloudflare Cache WordPress Posts and Pages Guide](https://guides.wp-bullet.com/cloudflare-cache-wordpress-posts-and-pages-guide/) - Cloudflare helps speed up WordPress and WooCommerce sites all around the world. Powered by more than 100 datacenters globally, Cloudflare’s CDN and security is a great addition to any web site.
* [18 Tips on How to Speed Up WordPress](https://www.keycdn.com/blog/speed-up-wordpress/) - WordPress is an amazing CMS platform, but it can also be quite slow if not optimized correctly. In this guide, we will show you how to speed up WordPress by sharing our web performance strategies and recommendations.
* [15 Website Speed Test Tools for Analyzing Web Performance](https://www.keycdn.com/blog/website-speed-test-tools/) - That is why it is important to take advantage of the many free website speed test tools available out there so you can achieve optimal performance.
* [Batch Optimize JPG Lossy Linux Command Line with jpeg-recompress](https://guides.wp-bullet.com/batch-optimize-jpg-lossy-linux-command-line-with-jpeg-recompress/) - Optimizing your images can feel like black magic sometimes. The safest JPG compression is lossless meaning no quality loss (guide), lossy compression has far superior space savings.
* [Cache AJAX GET Requests with Cloudflare and Varnish](https://guides.wp-bullet.com/cache-ajax-get-requests-with-cloudflare-and-varnish/) - AJAX requests are typically used to provide dynamic content on WordPress sites and bypass cache. I have already shown how to Cache AJAX requests with Varnish to bypass PHP and MySQL for AJAX processing by storing the cache in Varnish.

Hope this was helpful.

For any missing resources, please add them as issues. https://github.com/lukecav/awesome-wp-speed-up/issues
