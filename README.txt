=== Shortcuts for GeneratePress ===
Contributors: alvindcaesar
Donate link: https://alvindcaesar.com
Tags: generatepress, generateblocks
Requires at least: 5.0.0
Tested up to: 6.7
Stable tag: 1.0.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds a menu to the admin bar to easily jump straight into GeneratePress and GenerateBlocks menus and settings. Save all the clicks!

== Description ==

This plugin adds a handy "GP Shortcuts" menu item in the WP admin bar for quickly navigating to various areas within the site as well as to external sites relevant for the users of GeneratePress and GenerateBlocks.

== Installation ==

Ensure you have GeneratePress theme installed and active.

== Changelog ==

= 1.0.6 =
* Updated: Local Patterns shortcut now points to `wp_block` (Reusable Blocks). The legacy `gblocks_templates` post type is deprecated in GenerateBlocks Pro 2.6+.
* Updated: Global Styles shortcut now points to the new `generateblocks-styles` dashboard. The legacy `gblocks_global_style` post type is deprecated in GenerateBlocks Pro 2.6+.
* Updated: Local Patterns shortcut visibility is now gated by GenerateBlocks Pro presence rather than the legacy post type.

= 1.0.5 =
* Fixed: Resolved the issue where 'menu_page_url' function was not found.

= 1.0.4 =
* Compatibility with 6.4.2.

= 1.0.3 =
* Fixed an issue where the `GP Shortcuts` admin bar menu would not show up if the child theme's folder name was not using the default name.

= 1.0.2 =
* Reinstate the default location of the `Elements` menu bar.

= 1.0.1 =
* Menu's UX improvement

= 1.0.0 =
* Initial Release.