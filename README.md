# pcsd-tag-stripper

Plugin Name: PCSD Tag Stripper
Plugin URI: 
Author: espi
Requires at least: 3.0
Tested up to: 5.1.1
Version: 1.6
Tags: deprecated, remove, delete, nonbrakespace, nbsp, line-brake, line brake


Removes common deprecated and problematic tags and attributes that the Wordpress editor will add automatically. 

Original Code pulled and from a plugin ericjuden had written. modified by Josh Espinoza

This plugin will strip out the following tags:
<code>
rel=""
target=""
br /
br/
BR/
br
br
b
/b
non breaking space
Empty Headings 1 - 6
iframes
mailto:
</code>
# Installation
 - Copy the plugin files to <code>wp-content/plugins/</code>
 - Activate Plugin from the plugins page


# Changelog
 1.6
* added mailto: anchors, and iframes to the filtering out list
 1.5
* prepped for wordpress svn system
 1.3
* added additional tags to be removed
 1.2
* Initial release