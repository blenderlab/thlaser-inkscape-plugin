THLaser Inkscape Plugin
-----------------------

This program is an Inkscape extension for exporting a set of paths and
bitmap images as gcode script as supported by this marlin fork:
https://github.com/emente/buildlog-lasercutter-marlin

This script is a fork of the think|haous hacker space plugin.

This script is a fork of Gcodetools v1.2 written by Nick Drobchenko and
is released under the same license (GPL v2).

Installation
------------

Install Python Image Library: 
http://www.pythonware.com/products/pil/

Copy the files thlaser2.py and thlaser2.inx into your Inkscape extensions
folder. Fire up inkscape and you will find the plugin under Extensions ->
Export -> THLaser GCode Export.

Keyboard Shortcut
-----------------

You may find it handy to assign the extension to a keyboard shortcut. 
Include something like the following line to your inkscape keys 
preferences file (this will bind the plugin to Ctrl+\):

<bind key="backslash" modifiers="Ctrl" action="org.thinkhaus.filter.thlaser" display="true"/>

You can find your keyboard preferences file:

* On Linux: ~/.config/inkscape/keys/default.xml
* Windows:  %UserProfile%\Application Data\Inkscape\keys\default.xml

If that file doesn't exist, create it and include the following:

<?xml version="1.0"?>
<keys name="My Keys">
<bind key="backslash" modifiers="Ctrl" action="org.thinkhaus.filter.thlaser" display="true"/>
</keys>

