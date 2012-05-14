# Andro

**Andro** is a theme for MacRabbit's Espresso, that I made and am using. Expect updates, as I fiddle with the details.
I will also be porting Andro to several other editors in the near future, such as TextMate and Notepad++

Languages that are currently supported:

## HTML 
![HTML](https://github.com/cyrilmengin/andro/raw/master/examples/AndroExampleHTML.png)

## CSS, LESS, SASS
![CSS](https://github.com/cyrilmengin/andro/raw/master/examples/AndroExampleCSS.png)

## JavaScript 
![JavaScript](https://github.com/cyrilmengin/andro/raw/master/examples/AndroExampleJS.png)

## PHP
![PHP](https://github.com/cyrilmengin/andro/raw/master/examples/AndroExamplePHP.png)

## Python
![Python](https://github.com/cyrilmengin/andro/raw/master/examples/AndroExamplePython.png)

Porting to other Editors
------------------------

If you're going to port Andro to another editor, please let me know, and I'll add it. 
Note that getting the same effect is pretty hard, as not many editors enable you to have as much flexibility as Espresso.
Editor themes in the ``theme`` directory with a ``+`` in front of their names mean that they aren't a full port, that some things were lost.

License
-------

You can do whatever the hell you want. Really.
Use it, share it, modify it, smash it against the wall if you feel like it!
Be nice though, I'd appreciate a mention as the original author if you're going to be sharing / building on it.

# Installing Andro

All the files for the various IDEs are in the ``theme`` folder. Folders with a ``+`` in front of them means it isn't a full port and that some styling may not have been replicated, from the original Espresso version. 

Also, I suggest you use **Monaco** as your font, at **11pt** or **12pt**, depending on what looks best in your editor.

Espresso
--------

Copy the the ``themes/Espresso/Andro.css`` file to ``~/Library/Application Support/Espresso/Themes/Andro.css``.
Open up Espresso,  go to ``Espresso ➜ Preferences ➜ Colors`` and set your "active theme" to Andro.

The .SCSS file that I used for generating the ``Andro.css`` file is also available in there, if you decide to edit it yourself.
(If you do, make sure to let me know! I'll gladly accept improvements for it.)

TextMate
--------

Open up the ``themes/+TextMate/Andro.tmTheme`` file in TextMate (nothing should happen, but the app should open). 
Then select "Andro" as your theme in ``TextMate ➜ Preferences ➜ Fonts and Colors``.
**Note that this is not a full port. Some of the styling visible on the Espresso screenshots was not possible to replicate with TextMate.



