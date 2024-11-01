=== Xtreme One Toolbar ===
Contributors: daveshine, deckerweb
Donate link: http://genesisthemes.de/en/donate/
Tags: toolbar, adminbar, admin bar, xtreme one, xtreme one framework, xtreme theme, administration, resources, links, theme, settings, manage, deckerweb, ddwtoolbar
Requires at least: 3.6
Tested up to: 3.8
Stable tag: 1.2.0
License: GPL-2.0+
License URI: http://www.opensource.org/licenses/gpl-license.php

This plugin adds useful admin links and resources for the Xtreme One Theme Framework to the WordPress Toolbar / Admin Bar.

== Description ==

> #### Quick Access to Xtreme One Framework Resources - Time Saver!
> This plugin just adds **a lot Xtreme One Framework related resources** to your toolbar / admin bar. Also links to **all settings pages** of this framework are added making life for webmasters a lot easier. So you might just switch from the frontend of your site to the Xtreme One 'Xtreme Widget Manager' or adjust the 'Framework Settings' etc. -- Use this time saver and get quicker access :-)

**Please note:** The plugin requires the *Xtreme One Theme Framework* (in version 1.5.3 or higher), a paid premium product released by Inpsyde GmbH (via marketpress.com).

= General Features =
* The plugin is **primarily intended towards site admins and webmasters**.
* All the Framework settings links, plus support for all official child themes.
* Support for the most popular & best WordPress SEO plugins included (see below for listing).
* A massive list of official resource links is included: support forums, tutorials, documentation, translations etc.
* The added menu items by the plugin follow the same user cabalities as their original links - in other words: if a link to a settings page is not displayed without my plugin for a certain user role/capability it won't be when my plugin is active!
* 10 additional icon colors included :) (changeable via filters)
* 4 filters included to change wording/tooltip and icon of the main item - for more info [see FAQ section here](http://wordpress.org/plugins/xtreme-one-toolbar/faq/)
* For custom "branding" or special needs a few sections like "Extensions" and "Resource links group" could be hidden from displaying via your active child theme - for more info [see FAQ section here](http://wordpress.org/plugins/xtreme-one-toolbar/faq/)
* Fully internationalized! Real-life tested and developed with international users in mind!
* Fully WPML compatible!

= Special Features =
* This time supporting all official Xtreme One sites
* Switching between German and English/ International locale happens automatically based on your set WordPress locale in wp-config - as the official framework site is bilingual so is this plugin!!!
* Link to downloadable German language packs - only displayed when German locales are active (de_DE, de_AT, de_CH, de_LU)
* If the Xtreme One ecosystem grows more and more I will also add third-party and user links of course... :)
* *NOTE:* I would be happy to add more language/locale specific resources and more useful third-party links - just contact me!

Again, as the name suggests this plugin is **intended towards site admins and webmasters**. The new admin bar entries will only be displayed if the current user has the WordPress capability of `mange_options`. (Note: I am open for suggestions here if this should maybe changed to a more suitable capability.)

= Plugin/ Theme Support =
* Since version 1.1.0 of the plugin all official child themes to date are supported: "Blank" (packaged with framework), "Minimalist", "Indoor", "Draft", "VintageFolio", "Tuscany".
* *Since version 1.1.0 of the plugin the following premium & free SEO plugins are supported:*
 * "wpSEO" by Sergej Mueller (see: wpseo.de) (premium)
 * "WordPress SEO by Yoast" by Joost de Valk/ Yoast.com (free)
 * "All In One SEO Pack" by Michael Torbert (free version)
 * "All In One SEO Pack Pro" by Michael Torbert (premium version)
 * "SEO Ultimate" by SEO Design Solutions (free)
 * "gdHeadSpace4" by Milan Petrovic at Dev4Press (free)
 * "HeadSpace2" by John Godley (free)
* Note: As more official or third-party child themes and plugins become available I'll add support if possible.
* *Your plugin? - [Just contact me with specific data](http://genesisthemes.de/en/contact/)*

= Localization =
* English (default) - always included
* German - always included
* .pot file (`xtreme-one-toolbar.pot`) for translators is also always included :)
* Easy plugin translation platform with GlotPress tool: [Translate "Xtreme One Toolbar"...](http://translate.wpautobahn.com/projects/wordpress-plugins-deckerweb/xtreme-one-toolbar)
* *Your translation? - [Just send it in](http://genesisthemes.de/en/contact/)*

Credit where credit is due: This plugin here is inspired and based on the work of Remkus de Vries @defries and his original "WooThemes Admin Bar Addition" plugin.

[A plugin from deckerweb.de and GenesisThemes](http://genesisthemes.de/en/)

= Feedback =
* I am open for your suggestions and feedback - Thank you for using or trying out one of my plugins!
* Drop me a line [@deckerweb](https://twitter.com/deckerweb) on Twitter
* Follow me on [my Facebook page](https://www.facebook.com/deckerweb.service)
* Or follow me on [+David Decker](https://plus.google.com/+DavidDecker/posts) on Google Plus ;-)

= More =
* [Also see my other plugins](http://genesisthemes.de/en/wp-plugins/) or see [my WordPress.org profile page](http://profiles.wordpress.org/daveshine/)
* Tip: [*GenesisFinder* - Find then create. Your Genesis Framework Search Engine.](http://genesisfinder.com/)

== Installation ==

**NOTE:** Only works with *Xtreme One Framework* version 1.5.3 or higher as the parent theme. This is a paid premium product by Inpsyde GmbH, available via marketpress.com.

= Installation Steps =
1. Installing alternatives:
 * *via Admin Dashboard:* Go to 'Plugins > Add New', search for "Xtreme One Toolbar", click "install"
 * *OR via direct ZIP upload:* Upload the ZIP package via 'Plugins > Add New > Upload' in your WP Admin
 * *OR via FTP upload:* Upload `xtreme-one-toolbar` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Look at your toolbar / admin bar and enjoy using the new links there :)
4. Go and manage your framework settings :)

**Note:** The "Xtreme One Theme Framework" in version 1.5.3 or higher is required for this plugin in order to work. If you don't own a copy it yet, this premium parent theme has to be bought. More info about that you'll find here: marketpress.com

**Also note:** This plugin has NO settings page because I believe it's just not neccessarry. All customizing could be done via hooks, filters, constants and regular WordPress user roles & capabilities. As the plugin is indended for an admin/ webmaster use that's the way to go. This way we can save the overhaul of an options panel/settings page, additional database requests, uninstall routines and such. End result: a lightweight system that just works and saves clicks & time :-).

**Multisite install:** Yes, it's fully compatible but have a look in the [FAQ section here](http://wordpress.org/plugins/xtreme-one-toolbar/faq/) for more info :)

**Own translation/wording:** For custom and update-secure language files please upload them to `/wp-content/languages/xtreme-one-toolbar/` (just create this folder) - This enables you to use fully custom translations that won't be overridden on plugin updates. Also, complete custom English wording is possible with that, just use a language file like `xtreme-one-toolbar-en_US.mo/.po` to achieve that (for creating one see the tools on "Other Notes").

== Frequently Asked Questions ==

= Does this plugin work with latest WordPress version and also older versions? =
Yes, this plugin works really fine with the latest WordPress 3.6+, of course also WordPress 3.8! :-)
And sorry, it DOES NOT work with older WordPress versions so please update your install if you haven't done yet :).

= How are new resources being added to the admin bar? =
Just drop me a note on [my Twitter @deckerweb](https://twitter.com/deckerweb) or via my contact page and I'll add the link if it is useful for admins/ webmasters and the Xtreme One community.

= How could my plugin/ extension or child theme options page be added to the admin bar links? =
This is possible of course and highly welcomed! Just drop me a note on [my Twitter @deckerweb](https://twitter.com/deckerweb) or via my contact page and we sort out the details!
Particularly, I need the admin url for the primary options page (like so `wp-admin/admin.php?page=foo`) - this is relevant for both, plugins and themes. For themes then I also need the correct name defined in the stylesheet (like so `Footheme`) and the correct folder name (like so `footheme-folder`) because this would be the template name when using with child themes. (I don't own all the premium stuff myself yet so you're more than welcomed to help me out with these things. Thank you!)

= Is this plugin Multisite compatible? =
Yes, it is! :) Works really fine in Multisite invironment - here I just recommend to activate on a per site basis so to load things only where and when needed.

= In Multisite, could I "network activate" this plugin? =
Yes, you could! Of course it makes only sense if you have one or more sites running with Xtreme One in your Multisite environment. However, it's a lightweight plugin but activation on a per site basis is the recommended way from my point of view. Almost all admin links are intended for a per-site use and not for network-related stuff.

Though intended for a per site use it could make some sense in such an edge case: if all of the sites in Multisite use the Xtreme One Framework and have lots of plugins in common. This might be the case if you use Multisite for multilingual projects, especially with that awesome plugin: http://wordpress.org/plugins/multilingual-press/

= Can custom menu items be hooked in via child theme or other plugins? =
Yes, this is possible since version 1.1.0 of the plugin! There are two action hooks available for hooking custom menu items in -- `xotb_custom_main_items` for the main section and `xotb_custom_group_items` for the resource group section. Here's an example code:
`
add_action( 'xotb_custom_group_items', 'xotb_custom_additional_group_item' );
/**
 * Xtreme One Toolbar: Custom Resource Group Items
 *
 * @global mixed $wp_admin_bar
 */
function xotb_custom_additional_group_item() {

	global $wp_admin_bar;

	$wp_admin_bar->add_menu( array(
		'parent' => 'ddw-xtreme-xobar',
		'title'  => __( 'Custom Menu Item Name', 'your-textdomain' ),
		'href'   => 'http://deckerweb.de/',
		'meta'   => array( 'title' => __( 'Custom Menu Item Name Tooltip', 'your-textdomain' ) )
	) );
}
`

= Can certain sections be removed? =
Yes, this is possible! You can remove the following sections: "Child Theme" area (all items) / "Extensions" (main item + sub items!) / "Resources link group" at the bottom (all items) / "German language stuff" (all items)

To achieve this add one, some or all of the following constants to your child theme's `functions.php` file:
`
/** Xtreme One Toolbar: Remove Theme Items */
define( 'XOTB_THEME_DISPLAY', FALSE );

/** Xtreme One Toolbar: Remove Extensions Items */
define( 'XOTB_EXTENSIONS_DISPLAY', FALSE );

/** Xtreme One Toolbar: Remove Resource Items */
define( 'XOTB_RESOURCES_DISPLAY', FALSE );

/** Xtreme One Toolbar: Remove German Language Items */
define( 'XOTB_DE_DISPLAY', FALSE );
`

= Can the the whole toolbar entry be removed, especially for certain users? =
Yes, that's also possible! This could be useful if your site has special user roles/capabilities or other settings that are beyond the default WordPress stuff etc. For example: if you want to disable the display of any "Xtreme One Toolbar" items for all user roles of "Editor" please use this code:
`
/** Xtreme One Toolbar: Remove all items for "Editor" user role */
if ( current_user_can( 'editor' ) ) {
	define( 'XOTB_DISPLAY', FALSE );
}
`

To hide only from the user with a user ID of "2":
`
/** Xtreme One Toolbar: Remove all items for user ID 2 */
if ( 2 == get_current_user_id() ) {
	define( 'XOTB_DISPLAY', FALSE );
}
`

To hide items only in frontend use this code:
`
/** Xtreme One Toolbar: Remove all items from frontend */
if ( ! is_admin() ) {
	define( 'XOTB_DISPLAY', FALSE );
}
`

In general, use this constant do hide any "Xtreme One Toolbar" items:
`
/** Xtreme One Toolbar: Remove all items */
define( 'XOTB_DISPLAY', FALSE );
`

= Can I remove the original Toolbar items for WordPress SEO by Yoast? =
Yes, this is also possible! Since v1.1.0 of my plugin support for Yoast's great plugin is included so if you only want his stuff to appear within "Xtreme One Toolbar" just add this constant to your active child theme's `functions.php file` or a functionality plugin:
`
/** Xtreme One Toolbar: Remove original Yoast SEO items */
define( 'XOTB_REMOVE_WPSEO_YOAST_TOOLBAR', true );
`

= Can I remove the original Xtreme One Dashboard widget? =
Yes, also possible :) - I've included a helper function for that too!
`
/** Xtreme One Toolbar: Remove the 'Xtreme News' Dashboard widget */
add_action( 'init', '__xotb_remove_xtreme_dashboard_widget' );
`


= Available Filters to Customize More Stuff =
All filters are listed with the filter name in bold and the below additional info, helper functions (if available) as well as usage examples.

**xotb_filter_capability_all**

* Default value: `edit_posts` (needed for the "manage content" stuff...)
* 5 Predefined helper functions:
 * `__xotb_admin_only` -- returns `'administrator'` role -- usage:
`
add_filter( 'xotb_filter_capability_all', '__xotb_admin_only' );
`
 * `__xotb_role_editor` -- returns `'editor'` role -- usage:
`
add_filter( 'xotb_filter_capability_all', '__xotb_role_editor' );
`
 * `__xotb_cap_edit_theme_options` -- returns `'edit_theme_options'` capability -- usage:
`
add_filter( 'xotb_filter_capability_all', '__xotb_cap_edit_theme_options' );
`
 * `__xotb_cap_install_plugins` -- returns `'install_plugins'` capability -- usage:
`
add_filter( 'xotb_filter_capability_all', '__xotb_cap_install_plugins' );
`
* Another example:
`
add_filter( 'xotb_filter_capability_all', 'custom_xotb_capability_all' );
/**
 * Xtreme One Toolbar: Change Main Capability
 */
function custom_xotb_capability_all() {
	return 'switch_themes';
}
`
--> Changes the capability to `switch_themes`

**xotb_filter_main_icon**

* Default value: Xtreme One "X" logo (favicon) :)
* 10 Predefined helper functions for the 10 included colored icons, returning special colored icon values - the helper function always has this name: `__xotb_colornamehere_icon()` this results in the following filters ready for usage:
`
add_filter( 'xotb_filter_main_icon', '__xotb_blue_icon' );

add_filter( 'xotb_filter_main_icon', '__xotb_gray_icon' );

add_filter( 'xotb_filter_main_icon', '__xotb_green_icon' );

add_filter( 'xotb_filter_main_icon', '__xotb_khaki_icon' );

add_filter( 'xotb_filter_main_icon', '__xotb_orange_icon' );

add_filter( 'xotb_filter_main_icon', '__xotb_pink_icon' );

add_filter( 'xotb_filter_main_icon', '__xotb_red_icon' );

add_filter( 'xotb_filter_main_icon', '__xotb_tan_icon' );

add_filter( 'xotb_filter_main_icon', '__xotb_turquoise_icon' );

add_filter( 'xotb_filter_main_icon', '__xotb_yellow_icon' );

add_filter( 'xotb_filter_main_icon', '__xotb_child_images_icon' );
`
--> Where the last helper function returns the icon file (`icon-xotb.png`) found in your current child theme's `images` subfolder

* Example for using with current child theme:
`
add_filter( 'xotb_filter_main_icon', 'custom_xotb_main_icon' );
/**
 * Xtreme One Toolbar: Change Main Icon
 */
function custom_xotb_main_icon() {
	return get_stylesheet_directory_uri() . '/images/custom-icon.png';
}
`
--> Uses a custom image from your active child theme's `/images/` folder
--> Recommended dimensions are 16px x 16px

**xotb_filter_main_icon_display**

* Returning the CSS class for the main item icon
* Default value: `icon-xtreme` (class is: `.icon-xtreme`)
* 1 Predefined helper function:
 * `__xotb_no_icon_display()` -- usage:
`
add_filter( 'xotb_filter_main_icon_display', '__xotb_no_icon_display' );
`
 * This way you can REMOVE the icon!
* Another example:
`
add_filter( 'xotb_filter_main_icon_display', 'custom_xotb_main_icon_display_class' );
/**
 * Xtreme One Toolbar: Change Main Icon CSS Class
 */
function custom_xotb_main_icon_display_class() {
	return 'your-custom-icon-class';
}
`
--> You then have to define CSS rules in your theme/child theme stylesheet for your own custom class `.your-custom-icon-class`
--> Recommended dimensions are 16px x 16px

**xotb_filter_main_item**

* Default value: "Xtreme One"
* Example code for your child theme's `functions.php` file:
`
add_filter( 'xotb_filter_main_item', 'custom_xotb_main_item' );
/**
 * Xtreme One Toolbar: Change Main Item Name
 */
function custom_xotb_main_item() {
	return __( 'Your custom main item', 'your-child-theme-textdomain' );
}
`

**xotb_filter_main_item_tooltip**

* Default value: "Xtreme One Framework"
* Example code for your child theme's `functions.php` file:
`
add_filter( 'xotb_filter_main_item_tooltip', 'custom_xotb_main_item_tooltip' );
/**
 * Xtreme One Toolbar: Change Main Item Name's Tooltip
 */
function custom_xotb_main_item_tooltip() {
	return __( 'Your custom main item tooltip', 'your-child-theme-textdomain' );
}
`

**xotb_filter_xtreme_name**

* Default value: "Xtreme"
* Used for some items within toolbar links to enable proper branding
* Change things like in the other examples/principles shown above

**xotb_filter_xtreme_name_tooltip**

* Default value: "Xtreme One"
* Used for some items within toolbar links to enable proper branding
* Change things like in the other examples/principles shown above

**Final note:** If you don't like to add your customizations to your child theme's `functions.php` file you can also add them to a functionality plugin or an mu-plugin. This way you can also use this better for Multisite environments. In general you are then more independent from child theme changes etc.

All the custom & branding stuff code above can also be found as a Gist on Github: https://gist.github.com/2519992 (you can also add your questions/ feedback there :)

== Screenshots ==

2. Xtreme One Toolbar in action (English default version) ([Click here for larger version of screenshot](https://www.dropbox.com/s/6hu9f3v9nvaea4z/screenshot-1.png))

3. Xtreme One Toolbar in action - German translation :) ([Click here for larger version of screenshot](https://www.dropbox.com/s/zyhllpt3cxe967h/screenshot-2.png))

4. Xtreme One Toolbar in action - plugin help tab ([Click here for larger version of screenshot](https://www.dropbox.com/s/b5fnhwk7xmotob5/screenshot-3.png))

== Changelog ==

= 1.2.0 (2014-01-22) =
* UPDATE: Throughout the plugin applied owner and a bit of branding change since the new owner "Inpsyde GmbH" took over some months ago...
* UPDATE: Fixed all changed external resouces links.
* UPDATE: Removed some expired resource links.
* NEW: Added admin link to built-in inline documentation, since Xtreme One v1.5.3.
* NEW: Added help tab on Xtreme One main settings page.
* CODE: Code/ documentation updates & improvements; also partly refactoring.
* UPDATE: Updated German translations and also the .pot file for all translators.
* UPDATE: Initiated new three digits versioning, starting with this version.
* UPDATE: Extended GPL License info in readme.txt as well as main plugin file.
* NEW: Easy plugin translation platform with GlotPress tool: [Translate "Xtreme One Toolbar"...](http://translate.wpautobahn.com/projects/wordpress-plugins-deckerweb/xtreme-one-toolbar)

= 1.1.0 (2012-04-29) =
* *Extended possibilities for users to customize/brand the plugin output:*
 * NEW: Added two action hooks for hooking custom menu items in -- `xotb_custom_main_items` for the main section and `xotb_custom_group_items` for the resource group section (See FAQ section here for more info on that).
 * NEW: Added filter for main item icon to use custom icon.
 * NEW: Added filters for main item name to use a custom or no name (for example only keep the icon...) plus: for main item name's tooltip
 * NEW: Added alternate main Icon in 10 additional colors (changeable via filters)
 * NEW: Added possibility to remove certain sections - in general or for certain conditions (user roles, user ID's etc.)
 * *For more info on that topic and for code examples for filters and constants [see the FAQ section here](http://wordpress.org/plugins/xtreme-one-toolbar/faq/)*
 * NEW: Added helper function to remove the original "Xtreme News" Dashboard widget in the admin.
 * NEW: Added helper function to remove the original toolbar items of "WordPress SEO by Yoast" plugin if installed.
* NEW: Added child theme support for the 6 Xtreme One Child Themes; and also a fallback for custom child themes :)
* NEW: Added plugin support for the premium SEO plugin "wpSEO" by Sergej Mueller.
* NEW: Added plugin support for these popular free SEO plugins: "WordPress SEO by Yoast", "All In One SEO Pack" by Michael Torbert, "SEO Ultimate" by SEO Design Solutions, "gdHeadSpace4" by Milan Petrovic at Dev4Press and "HeadSpace2" by John Godley.
* UPDATE: Display toolbar / admin bar items only for logged-in users.
* CODE: Minor code/documentation tweaks.
* UPDATE: Extended and improved readme.txt documentation here.
* UPDATE: Updated existing screenshots and added some new ones.
* UPDATE: Updated German translations as well as the .pot file for all translators!
* NEW: Added banner image on WordPress.org for better plugin branding :)

= 1.0.0 (2012-02-09) =
* Initial release

== Upgrade Notice ==

= 1.2.0 =
Some additions & improvements: Updated links, code and readme file. Further, updated .pot file for translators plus German translations.

= 1.1.0 =
Major updates & improvements: Added child theme & plugin support, plsu lots of hooks, filters and constants for customizing branding. Code/documentation updates. Further, updated .pot file for translators plus German translations.

= 1.0.0 =
Just released into the wild.

== Plugin Links ==
* [Translations (GlotPress)](http://translate.wpautobahn.com/projects/wordpress-plugins-deckerweb/xtreme-one-toolbar)
* [User support forums](http://wordpress.org/support/plugin/xtreme-one-toolbar)
* [Code snippets archive for customizing, GitHub Gist](https://gist.github.com/deckerweb/2519992)

== Donate ==
Enjoy using *Xtreme One Toolbar*? Please consider [making a small donation](http://genesisthemes.de/en/donate/) to support the project's continued development.

== Translations ==

* English - default, always included
* German: Deutsch - immer dabei! [Download auch via deckerweb.de](http://deckerweb.de/material/sprachdateien/xtreme-one-framework/#xtreme-one-toolbar)
* For custom and update-secure language files please upload them to `/wp-content/languages/xtreme-one-toolbar/` (just create this folder) - This enables you to use fully custom translations that won't be overridden on plugin updates. Also, complete custom English wording is possible with that as well, just use a language file like `xtreme-one-toolbar-en_US.mo/.po` to achieve that (for creating one see the following tools).

**Easy plugin translation platform with GlotPress tool:** [**Translate "Xtreme One Toolbar"...**](http://translate.wpautobahn.com/projects/wordpress-plugins-deckerweb/xtreme-one-toolbar)

*Note:* All my plugins are internationalized/ translateable by default. This is very important for all users worldwide. So please contribute your language to the plugin to make it even more useful. For translating I recommend the awesome ["Codestyling Localization" plugin](http://wordpress.org/plugins/codestyling-localization/) and for validating the ["Poedit Editor"](http://www.poedit.net/), which works fine on Windows, Mac and Linux.

== Additional Info ==
**Idea Behind / Philosophy:** Just a little leightweight plugin for all the Xtreme One Framework users out there to make their daily web admin life a bit easier. I'll try to add more plugin support if it makes some sense. So stay tuned :).

**Hooks, Filters and Constants for Customizing** See FAQ section here or step up to out Gist on GitHub: https://gist.github.com/deckerweb/2519992 (you can also add your questions/ feedback there :)

== Last but not least ==
**Special Thanks go out to my family for allowing me to do such spare time projects (aka free plugins) and supporting me in every possible way!**