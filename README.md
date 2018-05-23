# Intro to SEO

## Learning Objectives

- **Explain** what SEO is and why it's used
- **List** a handful of basic steps to take to improve SEO

## Framing: What is SEO?
* Search Engine Optimization. 
* Getting your site to show up first in Google
* Showing relevant data in the search results

## Undeniable Leader
[Look](https://www.statista.com/statistics/216573/worldwide-market-share-of-search-engines/)

## Basic Steps
### Use [Google's documentation](https://developers.google.com/webmasters/googleforwebmasters/) as your main resource.
How Google crawls and indexes your site is constantly changing, and there are TONS of tools that they provide that you should look into, like:
* [Search Console](https://support.google.com/webmasters/answer/6258314?hl=en&ref_topic=3309469)
* [Analytics](https://www.google.com/analytics/analytics/#?modal_active=none)
* [Mobile-friendly test](https://search.google.com/test/mobile-friendly)
* [Google Trends](https://trends.google.com/trends/)
* [Keyword Planner](https://adwords.google.com/home/tools/keyword-planner/#?modal_active=none)

## PageRank
One of the founding tools Google used to rank sites (why it eventually became a verb) is called PageRank. It's their patented algorithm, and you can [read all about it](https://en.wikipedia.org/wiki/PageRank). It's based on _how many other sites link to yours_.


### This outline is inspired by [Googles docs](https://support.google.com/webmasters/answer/7451184)
1. Tell Google to index your site
2. Upload Sitemap
2a. You can try modules like `express-sitemap` to generate a sitemap.xml for your express app
3. Add a unique `<title>` to the `<head>` of each page
4. Add a unique description `<meta>` tag to the head of each page
5. Understand the [Anatomy of a Search Snippet](https://www.youtube.com/watch?v=MOfhHPp5sWs)
6. Use heading tags to emphasize important text
7. Use important words in your domain and URL paths [example](https://www.google.com/search?ei=Kq0FW8iqCsLpzgLDg62YDg&q=black+shirt+brewing&oq=black+&gs_l=psy-ab.3.0.35i39k1j0i67k1l3j0i20i264k1j0i67k1j0l2j0i67k1j0i131k1.21026.21852.0.22632.6.6.0.0.0.0.142.693.0j6.6.0....0...1.1.64.psy-ab..0.6.692....0.Sq0G5Cv7n_g)
8. Make navigation very clear, like using breadcrumbs
9. Optimize your images, like using the `alt` tag
10. Use `rel=canonical` for similar URLs. [Read More] (https://support.google.com/webmasters/answer/139066?hl=en)
11. Make your site mobile-friendly
12. Promote your website, like registering your business with google or getting on yelp
13. Use google analytics

## HTML Notes
* Proper HTML boilerplate structure -> Easily crawlable by Google
* Structure content with headings
* Use semantic HTML (like `nav`, `body`, `article`, `section`, etc)
* add `alt` tags to images
* Google hits you for shitty CSS
* Google detects when you put a shit ton of hidden `h1` tags filled with all your keywords and dings you for it

## Other Notes
* WYSIWYG tools usually have tools that do a lot of these steps for you
* Square Space has SEO tools built in
* Yoast is the most popular WordPress plugin

## Resources
* [Square Space's Docs](https://support.squarespace.com/hc/en-us/articles/206744067) 
* [Yoast for Wordpress](https://wordpress.org/plugins/wordpress-seo/)
* [Search Console](https://support.google.com/webmasters/answer/6258314?hl=en&ref_topic=3309469)
* [Analytics](https://www.google.com/analytics/analytics/#?modal_active=none)
* [Mobile-friendly test](https://search.google.com/test/mobile-friendly)
* [Google Trends](https://trends.google.com/trends/)
* [Keyword Planner](https://adwords.google.com/home/tools/keyword-planner/#?modal_active=none)
