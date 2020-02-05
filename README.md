# Firefox Quantum Rounded Tabs v. 1.1

What it does
--------------
This one-simple-file solution reshapes Firefox Quantum's default tabs by:
* removing the bold line at the top of the selected tab;
* rounding the top corners;
* slightly separating and outlining the tabs.

See screenshots > the Silky Blue example (click Download for a bigger display). That 
example has a light background, but you can also have a dark one. See the other examples and 
the CSS file for that (customization).

The CSS file also colors the Bookmarks icons orange and removes 3 of the 4 objects from the address
bar. The applicable rules are at the bottom of the file, self-explanatory and customizable as 
well.


Preparations before installation
--------------------------------
1. Download and unzip the package, whereby the userChrome.css file is what it's all about. 
2. Make Windows show its file extensions if it doesn't do that already. See
https://www.howtogeek.com/205086/beginner-how-to-make-windows-show-file-extensions/. 
3. At first, select a light extra Firefox theme: hamburger menu > Customize > Themes. The theme 
Silky Blue can be downloaded from the Firefox Themes site.
4. Type `about:config` in the Firefox address bar and press Enter. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`. If there is such a rule, check that it's set to `true`. If no such rule, simply continue with the installation. 


Installation
------------
1. Type <code>about:support</code> in Firefox's address bar and press Enter.
2. On the appearing page, you will see 'Profile folder' in the left column. Click 'Open folder'.
3. In the appearing window, right-click and click 'New folder'. Give the folder the name <code>chrome</code>.
4. Copy or move the userChrome.css file to that folder.
5. Close & restart Firefox and enjoy your new interface. :-)


Going back to default
---------------------
Simply delete the file or the whole chrome folder and restart Firefox.


Customization
-------------
You have to be very careful with that, even if you know CSS. The problem is that Firefox's
internal CSS rules sometimes differ from web CSS rules. And its logic regarding classes, IDs 
and layers differs from (valid) HTML as well.

But you can and should change the tab text color to a light one if you want a dark theme.
For CSS color names and codes, see https://www.w3schools.com/colors/colors_names.asp.
The variables in the file that you can change without risk are followed by the comment
'customizable'. To open the CSS file after being installed, right-click > Open with > Notepad.


Problems and other comments
---------------------------
If you would encounter a problem and have a Github account, please start a <a href="https://github.com/FrankConijn/Firefox-Quantum-Rounded-Tabs/issues/new">New Issue</a>. Other comments are 
welcome at f [dot] conijn [at] conijnconsultancy [dot] com. 


Change log
----------
v. 1.1: Split the tab text color coding into two parts, one for all tabs and one for only the selected tab. 
