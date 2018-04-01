# Firefox Quantum Rounded Tabs

What it does
--------------
This one-file solution re-shapes Firefox Quantum's default tabs by:
* removing the light line at the top of the selected tab;
* rounding the top corners;
* slightly separating and outlining the tabs.

See the example image (right-click > View image to enlarge). That image has a light background, 
but you can also have a dark one. See the CSS file for that.

The file also colors the Bookmarks icons orange and removes 3 of the 4 objects in the address
bar. The applicable rules are at the bottom of the file, self-explanatory and customizable as 
well.


Preparations before installation
--------------------------------
1. Make Windows show its file extensions if it doesn't do that already. See
https://www.howtogeek.com/205086/beginner-how-to-make-windows-show-file-extensions/
2. At first, select a light Firefox theme: hamburger menu > Customize > Themes. The theme in my
example is Silky Blue, which you can download from the Firefox Themes site.


Installation
------------
1. Type about:support in Firefox's address bar and press Enter.
2. On the appearing page, you will see 'Profile folder' in the left column. Click 'Open folder'.
3. In the appearing window, at the top, click 'New folder'. Give the folder the name chrome.
4. Copy or move this file to that folder.
5. Close & restart Firefox and enjoy your new interface. :-)


Going back to default
---------------------
Simply delete the file or the whole chrome folder, and restart Firefox.


Customization
-------------
You have to be very careful with that, even if you know CSS. The problem is that Firefox's
internal CSS rules sometimes differ from web CSS rules. And its logic regarding the
'document object model' differs from (valid) HTML as well.

But you can and should change the tab text color to a light one if you want a dark theme.
For CSS color names and codes, see https://www.w3schools.com/colors/colors_shades.asp.
The variables in the file that you can change without risk are followed by the comment
'customizable'.


I like to hear how you like it.
