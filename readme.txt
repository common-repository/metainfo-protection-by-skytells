=== Skytells MetaInfo Protection ===
Contributors: Skytells Inc
Plugin URI: https://www.skytells.me/files/file/2-skytells-metainfo-protection-for-wordpress/
Author: Skytells, Inc
Author URI: https://www.skytells.org
Tags: remove, version, generator, security, meta, appended version, css ver, js ver, meta generator
Requires at least: 3.0
Tested up to: 4.9
Stable tag: 2.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin will remove the version info appended to enqueued style and script urls along with Meta Generator in the head section and in RSS feeds.

== Description ==

This plugin will remove the version information that gets appended to enqueued style and script urls. It will also remove the Meta Generator in the head and in RSS feeds. Adds a bit of obfuscation to hide the WordPress version number and generator tag that many sniffers detect automatically from view source. Option available to selectively exclude any style or script file from version info removal process.

You can enable/disable each removal options from admin dashboard:
<ol><li>Remove Meta Generator Tag</li>
<li>Remove Version from Stylesheet</li>
<li>Remove Version from Script</li>
<li>Exclude files from version info removal process (by providing comma separated file names)</li></ol>

You have any suggestions to make this plugin better? Please share your thoughts in the support thread.

Dashboard > Settings > Meta Generator and Version Info Remover

== Installation ==

1. Unzip the zipped file and upload to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Manage individual options from Dashboard > Settings > Meta Generator and Version Info Remover

== Frequently Asked Questions ==

= Can I exclude a script/css file? =

Yes! You can exclude any script/css files by providing the file names in comma separated format.

= Will this plugin cause any problem with WordPress update process? =

Not at all! It will cause no problem with WordPress update process.

== Screenshots ==

1. Setting page
2. Settings page with a list of files (comma separated list) to exclude from version info removal process
3. View source demo

== Changelog ==

= 2.0 =
* Plugin Tags fixed
= 1.0 =
* Initial Commit.

== Upgrade Notice ==

N/A.
