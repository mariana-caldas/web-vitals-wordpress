# Web Vitals for WordPress

In this repository, there are some notes referent to the **Core Web Vitals** (essential metrics that Google considers important in a webpage's overall user experience) especially related to WordPress.

<br />

## How do users experience or interact with my web products?

### Pilars of UX

1. **Loading** - *Is it happening?*
2. **Interactivity** - *Is it responsive?*
3. **Visual Stability** - *Is it delightful?*

### Metric Tresholds

![Metric Tresholds Image](https://github.com/MarianaSouza/web-vitals-wordpress/blob/main/metric-thresholds.png)

<br />

## Largest Content Paint - LCP (less than 2.5 sec)
*Loading*

Measures the render time of the largest content element (image or block of text) visible within the viewport.

### Recommendations to prevent or address it:

* Optimize your featured/landing/banner/hero image.
* Do not lazy-load images which are very likely to be in the initial viewport -> *How to remove lazy-load from those elements?*
* Use an [image CDN](https://imagekit.io/blog/what-is-image-cdn-guide/) to ensure fastest image loads.

<br />

## Cumulative layout Shift - CLS (less than 100 ms)
*Visual Stability*

Measures the sum of all unexpected layout shifts that occur thoughout the lifespan of a page.

### Recommendations to prevent or address it:

* Ensure images include width and height (update to WP 5.5) -> *That prevents content to shift around when images are finally loaded by making the browser to reserve a space for them beforehand*.
* Dynamic content: reserve space for content that renders dynamically (ads, JS widgets, social, login, discussion)

<br />

## First Input Delay - FID (less than 0.1)

<br />

### Web Vitals for WordPress Links

* https://web.dev/vitals/
* https://web.dev/fid/
* https://web.dev/lcp/ 
* https://web.dev/cls/
* https://bit.ly/web-vitals-science
* https://bit.ly/web-vitals-methodology 
* https://core.trac.wordpress.org/ticket/50367 
* https://core.trac.wordpress.org/ticket/50425
* https://core.trac.wordpress.org/ticket/12009#comment:57
* https://squoosh.app/ 
* https://www.youtube.com/watch?v=AQqFZ5t8uNc 
* https://make.wordpress.org/core/2020/07/14/lazy-loading-images-in-5-5/ 
* https://developers.google.com/speed/pagespeed/insights/
* https://web.dev/lighthouse-whats-new-6.0/
* https://web.dev/vitals-tools/
* https://github.com/GoogleChrome/web-vitals
* https://github.com/GoogleChrome/web-vitals-extension
* https://github.com/GoogleChrome/lighthouse-stack-packs
* https://newspack.pub/
* http://g.co/chromeuxdash
* https://developers.google.com/web/tools/chrome-user-experience-report/api/reference/
* https://developers.google.com/web/updates/2018/08/chrome-ux-report-dashboard 
* https://support.google.com/webmasters/answer/9205520
* Measure Web Vitals in Analytics - https://gist.github.com/adamsilverstein/c1734fd50c4e1f28c7428d1fc7ab2870 
* https://web.dev/vitals-field-measurement-best-practices/ 
* https://support.google.com/webmasters/answer/9205520
* https://web.dev/vitals-tools/
* Site monitoring App Script: https://gist.github.com/adamsilverstein/89b788447882a13b3f1222f9b950978c 
* Site Kit: https://sitekit.withgoogle.com 
* AMP-WP: https://amp-wp.org/ 
* Newspack: https://github.com/Automattic/newspack-plugin 
