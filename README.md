# RSS Feed Plugin #

## Description ##

This plugin lets you create campaigns that include content from RSS feeds and are automatically repeated at regular intervals.

The plugin adds a tab to the Send a campaign page on which you specify the URL of the RSS feed.
When the campaign is sent the content of the message has recent items, dependent on the repeat frequency, from the feed.


## Installation ##

### Dependencies ###

Requires php version 5.3 or later. 

Requires the Common Plugin version 2015-03-23 or later to be installed. You should install or upgrade to the latest version.

See <https://github.com/bramley/phplist-plugin-common>

### Set the plugin directory ###
The default plugin directory is `plugins` within the admin directory.

You can use a directory outside of the web root by changing the definition of `PLUGIN_ROOTDIR` in config.php.
The benefit of this is that plugins will not be affected when you upgrade phplist.

### Install through phplist ###
Install on the Plugins page (menu Config > Plugins) using the package URL `https://github.com/bramley/phplist-plugin-rssfeed/archive/master.zip`

In phplist releases 3.0.5 and earlier there is a bug that can cause a plugin to be incompletely installed on some configurations (<https://mantis.phplist.com/view.php?id=16865>). 
Check that these files are in the plugin directory. If not then you will need to install manually. The bug has been fixed in release 3.0.6.

* the file RssFeedPlugin.php
* the directory RssFeedPlugin

### Install manually ###
Download the plugin zip file from <https://github.com/bramley/phplist-plugin-rssfeed/archive/master.zip>

Expand the zip file, then copy the contents of the plugins directory to your phplist plugins directory.
This should contain

* the file RssFeedPlugin.php
* the directory RssFeedPlugin

###Settings###
The plugin adds an RSS group to the Settings page where you can enter:

* The minimum number of items to be included in a campaign. The default is 1.
* The maximum number of items to be included in a campaign. The default is 30.
* The item HTML template.

##Usage##

For guidance on using the plugin see the plugin's page within the phplist documentation site <https://resources.phplist.com/plugin/rssfeed>

##Support##

Questions and problems can be reported in the phplist user forum topic <http://forums.phplist.com/viewtopic.php?f=7&t=41650>.

## Donation ##
This plugin is free but if you install and find it useful then a donation to support further development is greatly appreciated.

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=W5GLX53WDM7T4)

## Version history ##

    version     Description
    2015-03-24  Release to GitHub