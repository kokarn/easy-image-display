=== Easy Image Display ===
Contributors: Shellbot
Tags: image, gallery, latest image, random image
Requires at least: 3.5
Tested up to: 3.8
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Display newest, oldest or random images uploaded to your site.

== Description ==

Sometimes you need a proper image gallery to display particular images, and there 
are plenty of plugins for that. Easy Image Display is for those other 
times, when all you need is an easy way to display some random images, or X latest/oldest 
images uploaded to your site.

Current features include:

* Include/exclude images based on ID
* Widget, shortcode and template tag for maximum flexibility
* Display images at various sizes
* Control how many images are displayed and in how many columns
* Link images to a lightbox, or remove link entirely
* Uses gallery shortcode so will always fit your theme

Features soon to be added:

* Filter images by attachment status
* Slideshow layout
* Custom image sizes

**Usage**

Easy Image Display provides 3 ways of displaying images; widget, shortcode and template tag. Each method accepts the same options and will result in the same display.

**Widget**

The Easy Image Display widget is the easiest way to display your images. The basic settings allow you to control image size, order and number. More advanced settings are collapsed by default to provide a simple uncluttered interface.

Choose your options, hit save, and rejoice.

**Shortcode**

To display images inside a post or page rather than a widget area, you need a shortcode.

Default settings:

`[sb_easy_image]`

Custom settings:

`[sb_easy_image num="1" order="random" link="lightbox"]`

**Template tag**

The template tag is available for users who are confident in adding code to theme files, and need to display images outside of the widget areas or main content area. The following function can be added anywhere in your theme files.

Default settings:

`<?php sb_easy_image(); ?>`

Custom settings:

`<?php

$args = array(
    "num" => "1",
    "order" => "random",
    "link" => "lightbox",
}

sb_easy_image( $args );

?>`

For full list of parameters see [the plugin release page](http://shellbotics.com/wordpress-plugins/easy-image-display/ "Easy Image Display")

== Installation ==

1. Upload the 'easy-image-display' folder to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Add images using the widget, shortcode or template tag
4. Enjoy!

== Frequently Asked Questions ==

= The widget always displays images in one column? =

Some themes handle gallery styling differently in different areas of the page. 
If your theme does not support multiple column galleries in a widget area you 
may need to add some custom CSS.

Every theme is different, but if you're unfamiliar with CSS and need some help 
please post in [the plugin support forum](http://wordpress.org/support/plugin/easy-image-display) with a link to your site.

== Changelog ==

= 1.1.0 =
* Fixed version numbering

= 1.0.2 =
* Added option to include/exclude images based on ID
* Fixed issue with widget form not expanding correctly

= 1.0.1 =
* Fixed an incompatibility with other lightbox plugins

= 1.0 =
* First version

== Upgrade Notice ==

= 1.1.0 =
* New feature! Include/exclude images based on ID.

= 1.0.2 =
* New feature! Include/exclude images based on ID.

= 1.0.1 =
Fixes an incompatibility with other lightbox plugins.
