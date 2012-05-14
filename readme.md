# Andro

**Andro** is a theme for MacRabbit's Espresso, that I made and am using. Expect updates, as I fiddle with the details.
I will also be porting Andro to several other editors in the near future, such as TextMate and Notepad++

Languages that are currently supported:

HTML
----
![HTML](https://github.com/cyrilmengin/andro/raw/master/examples/AndroExampleHTML.png)

CSS, LESS, SASS
---------------
![CSS](https://github.com/cyrilmengin/andro/raw/master/examples/AndroExampleCSS.png)

JavaScript 
----------
![JavaScript](https://github.com/cyrilmengin/andro/raw/master/examples/AndroExampleJS.png)

PHP
---
![PHP](https://github.com/cyrilmengin/andro/raw/master/examples/AndroExamplePHP.png)

Python
------
![Python](https://github.com/cyrilmengin/andro/raw/master/examples/AndroExamplePython.png)

# Porting to other Editors

If you're going to port Andro to another editor, please let me know, and I'll add it. 
Note that getting the same effect is pretty hard, as not many editors enable you to have as much flexibility as Espresso.

Here are the colors (credit goes to [@NeilHanlon](https://github.com/neilhanlon) for converting the HEX to RGB):

	$background: #292929;     :  rgb(41,41,41)
	$highlight: #3C3C3C;      :  rgb(60,60,60)
	$current: #303030;        :  rgb(48,48,48)
	
	$blue: #6B84A3;           :  rgb(107,132,163)
	$beige: #E8BF6A;          :  rgb(232,191,122)
	$white: #D6D6D6;          :  rgb(214,214,214)
	$brown: #676767;          :  rgb(103,103,103)
	$orange: #C24D43;         :  rgb(194,77,67)
	$grey: #B9AA99;           :  rgb(185,170,153)

# License

You can do whatever the hell you want. Really.
Use it, share it, modify it, smash it against the wall if you feel like it!
Be nice though, I'd appreciate a mention as the original author if you're going to be sharing / building on it.

# Installing Andro

All the files for the various IDEs are in the ``theme`` folder. 
Editor themes in the ``theme`` directory with a ``+`` in front of their names mean that they aren't a full port, that some things were lost.

Also, I suggest you use **Monaco** as your font, at **11pt** or **12pt**, depending on what looks best in your editor.

Espresso
--------

Copy the the ``themes/Espresso/Andro.css`` file to ``~/Library/Application Support/Espresso/Themes/Andro.css``.
Open up Espresso,  go to ``Espresso ➜ Preferences ➜ Colors`` and set your "active theme" to Andro.

The .SCSS file that I used for generating the ``Andro.css`` file is also available in there, if you decide to edit it yourself.

TextMate
--------

Open up the ``themes/+TextMate/Andro.tmTheme`` file in TextMate (nothing should happen, but the app should open). 
Then select "Andro" as your theme in ``TextMate ➜ Preferences ➜ Fonts and Colors``.

**Note that this is not a full port. Some of the styling visible on the Espresso screenshots was not possible to replicate with TextMate.**

Sublime Text 2
--------------

Copy the ``themes/+Sublime Text 2/Andro.tmTheme`` file to ``~/Library/Application Support/Sublime Text 2/Packages/User/Andro.tmTheme``.
Then open Sublime Text, and select ``Sublime Texte 2 ➜ Preferences ➜ Color Scheme ➜ User ➜ Andro``. Andro should now be your theme.

**Note that this is not a full port. Some of the styling visible on the Espresso screenshots was not possible to replicate with TextMate.**



