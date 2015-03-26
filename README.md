UM AAPS Student Chapter CMS
================
It's the official code for the website for [UM AAPS Student Chapter][umaaps], cloned and redsigned based on a nicely developed jekyll-based CMS site called [StrathSEDS.org][ss]. It uses [bootstrap](https://github.com/twitter/bootstrap), [jekyll][jk], [ruby][rb], [liquid], and [fancybox].

Requirements
------------

Development time dependencies:

* [Ruby][rb]
* [Gems][gm]
* [Jekyll][jk]
* [Rdiscount][rd] (optional - comment out in `_confing.yaml` to use Maroku)
* [Node.js][no] & [Grunt.js][gr] (optional - only if you wish to use GruntJS)

Run-time dependencies:

* A web server (any will do)


Fast Testing Guide
----------------------

To use this template:

1. Clone to some directory
* Modify `_config.yaml` with your name, blog title, description and etc...
* Tweak HTML files in `_layouts` to personalize.
* Create blog entries in `_posts/` - work off the sample posts there
* Deploy the site to github
* View it and make sure it looks good
* If all is well, upload contents of `_site` to your server
* Repeat steps 4-7 to update blog

Features
--------

Following features are available:

* Automatically generate a valid RSS feed (see feed.xml in root directory). (pending)
* Automatically generate a valid Google Sitemap (see sitemap.xml in root directory). (pending)
* Automatically generate a .htaccess file with error 404 & 500 support
* Automatically generate committee list using a dataset

Credits
-------

Based off of [Bootstrap](http://getbootstrap.org/)

Some code and framework design are nicely done by [StrathSEDS Group][ss]


Licence
-------

This code and content is under a [Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License][cc-l]. Permissions beyond the scope of this license cannot be granted without contacting the original author at chanyufei [at] gmail [dot] com.


[rb]: http://www.ruby-lang.org/
[gm]: http://rubygems.org/
[jk]: https://github.com/mojombo/jekyll
[rd]: https://github.com/rtomayko/rdiscount/
[dp]: http://recursive-design.com
[gr]: http://gruntjs.com
[no]: http://nodejs.com
[cc-l]: http://creativecommons.org/licenses/by-nc-nd/3.0/deed.en_US
[ss]: http://strathseds.org
[umaaps]:http://umaaps.github.io
[liquid]: https://github.com/Shopify/liquid/
[fancybox]: http://fancyapps.com/fancybox