# Linker #
[![Build Status](https://travis-ci.org/KingYes/wp-linker.svg?branch=master)](https://travis-ci.org/KingYes/wp-linker) [![Dependency Status](https://david-dm.org/KingYes/wp-linker/dev-status.svg)](https://david-dm.org/KingYes/wp-linker#info=devDependencies) [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

**Contributors:** pojo.me, KingYes, ariel.k  
**Tags:** click tracking, custom post types, redirect, 301, outbound links, pretty links, link manager, links, google analytics, affiliates, external links,  
**Requires at least:** 3.5  
**Tested up to:** 4.3  
**Stable tag:** 1.1.1  
**License:** GPLv2 or later  

Manage, create and track outbound links by custom pretty links with your domain. e.g. your-domain.com/go/fb-link

## Description ##

Linker is a simple & easy plugin to manage, create and track outbound links from your website. Linker adds a new custom post type to your Admin menu, where you can create, edit, delete, and manage Links by 301 redirects.

Linker is tracking click counts and save them of a custom field on that custom post type, it really simple & cool.

<h4>Integration with Google Analytics</h4>
You can track with Google Analytics to get full statistics by Event Tracking.

 This plugin work well too with [Google Analytics for WordPress](http://wordpress.org/plugins/google-analytics-for-wordpress/) by Yoast.

Go to the Setting Page of Google Analytics under the Setting Menu, and go to > Internal Links to Track as Outbound  > enter "/go/" in the field > choose Label to use.

Now you can show up in Analytics all clicks out. go to Content > Event Tracking > Categories, and you’ll see your Label that used. that's all.

<h4>Translators:</h4>
* Hebrew (he_IL) + RTL Support - [Pojo.me](http://pojo.me/)
* Brazilian Portuguese (pt_BR) - Rhenan Cardozo
* Indonesian (id_ID) - YiiBooster

<h4>Thanks</h4>
We took inspiration to our plugin from [Simple URL](http://wordpress.org/plugins/simple-urls/) plugin - so thank you so much, you done good job.

<strong>Contributions:</strong><br />

Would you like to like to contribute to Linker? You are more than welcome to submit your pull requests on the [GitHub repo](https://github.com/KingYes/wp-linker). Also, if you have any notes about the code, please open a ticket on ths issue tracker.


## Installation ##

1. Upload plugin files to your plugins folder or install using WordPress built-in Add New Plugin installer
1. Activate the plugin
1. Navigate to Settings > Permalinks and save them. Yes, just click Save Changes.
1. Go to the Linker Menu under the Pages
1. Create a new Link and publish
1. Now you can track how many times clicked on each link

## Screenshots ##

### 1. All Links ###
![All Links](http://s.wordpress.org/extend/plugins/linker/screenshot-1.png)

### 2. New Link ###
![New Link](http://s.wordpress.org/extend/plugins/linker/screenshot-2.png)


## Frequently Asked Questions ##

### Can I change the Link structure other than /go/ ? ###
* Sure. Just use with `linker_prefix_slug` filter.

### Requirements ###
* __Requires PHP5__ for list management functionality.

### What is the plugin license? ###
* This plugin is released under a GPL license.


## Changelog ##

### 1.1.1 ###
* Added translate: Indonesian (id_ID) Thanks to YiiBooster ([#20](https://github.com/KingYes/wp-linker/pull/20))

### 1.1.0 ###
* Added filter by Author ([#16](https://github.com/KingYes/wp-linker/pull/16))
* Added readonly field for Copy-Paste linker
* Updated Dashboard Output
* Dashboard info and CSS external file
* Tested up to WordPress v4.3

### 1.0.6 ###
* Added Dashboard Widget and Orderby clicks ([#13](https://github.com/KingYes/wp-linker/pull/13)).

### 1.0.5 ###
* Added translate: Brazilian Portuguese (pt_BR) Thanks to Rhenan Cardozo
* Tested up to WordPress v4.2.2

### 1.0.4 ###
* The plugin flush the permalinks automation.
* Tested up to WordPress v4.2

### 1.0.3 ###
* Tested up to WordPress v4.1

### 1.0.2 ###
* Tested up to WordPress v4.0

### 1.0.1 ###
* Added translate: Hebrew (he_IL) - Thanks to [Pojo.me](http://pojo.me/)

### 1.0.0 ###
* Blastoff!
