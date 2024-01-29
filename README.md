Captcha Plugin for Elgg 4.3 and newer Elgg 4.X
==============================================

Latest Version: 4.3.0  
Released: 2023-01-29  
Contact: iionly@gmx.de  
Website: https://github.com/iionly  
License: GNU General Public License version 2  
Copyright: (C) iionly 2012, (C) Curverider 2008


Description
-----------

Provides captcha support (Requires the php_gd library).
Only change made to iiolny's originalversion is I updated composer.json to include v4.3. appears to be fully fuctional in v4.3

Installation and configuration
------------------------------

1. If you have a previous version of the Captcha plugin installed, disable it and then remove the captcha folder from your mod directory before copying the new version on the server,
2. Copy the captcha plugin folder into you mod folder,
3. Enable the Captcha plugin in the admin section of your site.

The captcha plugin also works with the walled-garden option of Elgg core enabled. If you use the alternative walled-garden plugin loginrequired released by me, you need to place the captcha plugin above the loginrequired plugin in the plugin list on your site.
