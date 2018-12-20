# Shift8 Facebook Feed 
* Contributors: shift8
* Donate link: https://www.shift8web.ca
* Tags: facebook feed, facebook shortcode, fb shortcode
* Requires at least: 3.0.1
* Tested up to: 5.0.2
* Stable tag: 1.0.3
* License: GPLv3
* License URI: http://www.gnu.org/licenses/gpl-3.0.html

Plugin that easily integrates your facebook page's feed into your Wordpress site.

## Description 

This is a small plugin that allows you to easily integrate your Facebook page's feed into your Wordpress site. You simply define your Facebook App info in the settings and utilize the shortcode + options to inject the Facebook page's feed into your site.

The shortcode generates straightforward markup with custom CSS classes that allow you to style and arrange the feed however you see fit. 

## Installation 

This section describes how to install the plugin and get it working.

e.g.

1. Upload the plugin files to the `/wp-content/plugins/shif8-fbfeed` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Navigate to the plugin settings page and define your Facebook page name + Facebook Application key/secret.
3. Use the shortcode markup anywhere in your site to integrate the feed


## Frequently Asked Questions 

### What are the shortcode options? 

An example shortcode would be the following :

<pre>
[shift8-fbfeed number="5"]
</pre>

Where "number" is the number of posts to pull from the feed (From latest backwards)

### How can I style the markup? 

The markup that is generated encapsulates everything in a div container with the class "frontfb-item". You can use this class in your CSS to style the feed however you want.

### What else have you done?

You can visit [our website](https://www.shift8web.ca "Toronto Web Design") to see! :)

### Screenshots 

1. This is the options page where you define the Facebook App information and Facebook page name
2. This is an example of how the feed looks, with CSS styling of course

## Changelog 

### 1.0.0
* Stable version created
* Implemented short code options
### 1.0.1
* Added support for latest WP version
### 1.0.2
* Added support for latest WP version
### 1.0.3
* Wordpress 5 compatibility
