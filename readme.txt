=== Simple Link List Widget ===
Contributors: jimmywb, frankieroberto
Tags: links, list, lists, widget
Requires at least: 2.8
Tested up to: 3.0.4
Stable tag: 0.1

This plugin makes a widget available which allows you to add a simple link list (bulleted or numbered) to a sidebar.

== Installation ==

Install this plugin in the usual way, by downloading and unzipping the folder into your plugins directory (/wp-content/plugins).

The plugin then needs to be activated before it can be used.

To use, simply drag the 'List' widget into a sidebar. To use the widget, your theme must be widget-enabled.

== Frequently Asked Questions ==

= How do I style the list? =

You can style your list by adding the following code to the style.css file in your chosen theme:

    /* Styles for Simple Link List Widget */
    .widget_link_list ul {} /* Style for unordered list */
    .widget_link_list ol {} /* Style for ordered list */
    .widget_link_list ul li {} /* Style for unordered list item */
    .widget_link_list ol li {}  /* Style for ordered list item */

In addition you can add a custom style to the list items that will be added to the li tag of the list.

== Screenshots ==

1. Widget editing interface.

== Changelog ==

= 0.1 =
* Initial upload