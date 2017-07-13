**NOTE:** Due to Colloquy not having received an update since 2014, I will no longer actively maintain this theme. A version of the theme for the Textual IRC client is being worked on here: <https://github.com/TempSpas/textual-succinct>.

Three reasons to love Succinct
------------------------------

1. Simple, clean design.
2. Emphasizes what you need.
3. De-emphasizes what you don’t.

Succinct is a theme for the [Colloquy IRC client](http://colloquy.info/) for macOS. The goal of this fork is to add some color and appearance tweaks of my own, reducing contrast and improving chat room readability. Changes to usability include:
* Unique nickname coloring (courtesy of [willasaywhat](https://github.com/willasaywhat))
* Getting rid of text shadows
* Member links and URLs maintaining color in chat events

I also added two variants, Solarized and Solarized Dark, based on http://ethanschoonover.com/solarized, giving the theme another light option and a decent "night mode." Aside from these changes, I added descriptive comments where I could to allow end users to seek and change any part of it, much like I did when I discovered the style for the first time.

Default:

<img src="https://raw.githubusercontent.com/TempSpas/succinct-for-colloquy/master/Default.png" alt="Screenshot" />

Solarized:

<img src="https://raw.githubusercontent.com/TempSpas/succinct-for-colloquy/master/Solarized.png" alt="Screenshot" />

Solarized Dark:

<img src="https://raw.githubusercontent.com/TempSpas/succinct-for-colloquy/master/Dark.png" alt="Screenshot" />

Note: Because of the plethora of colors possible for nicknames, some may not look right
on certain themes. It's a work in progress; I'm still changing them as I notice them
to fit each one just right. Each variant's CSS has all of the colors labeled if you'd like
to seek out and change any you spot that don't fit.

Download & Install Instructions:
--------------------------------

If you're finding this theme by google and don't really know what you're doing, you're
exactly like me when I found the original. Steps to download:

1. [Download this file](https://github.com/TempSpas/succinct-for-colloquy/archive/master.zip) and unzip it.
2. Move all the contents of the folder except "Succinct.colloquyStyle" to the trash. (These are just things like the screenshots, the changelog, this file; you don't need them to use the style).
3. Open an additional Finder window and, from the Finder's "Go" menu, select
   "Go to Folder..." . In the dialog pane that appears, enter:
     ```/Library/Application Support/Colloquy/Styles``` (If this fails, type ```/Library/Application Support``` and
     create a folder called "Colloquy". Inside that, create one called "Styles").
4. Drag "Succinct.colloquyStyle" there.
5. Type ```/reload styles``` into Colloquy. (If this fails, restart Colloquy).

Variants of Succinct will now be selectable themes in the Styles dropdown menu or in the preferences.

Editing Instructions:
---------------------

Again, when I found the original theme, I wanted to change a lot of the colors and appearance myself,
beyond what Colloquy allows you to do in the preferences menu. (Plus it's 
[bugged](http://colloquy.info/project/ticket/4307)). Here are instructions to tweak
the themes to your liking if you've already downloaded them.

1. Locate the file. (Open a Finder window and, from the "Go" menu, select "Go to Folder..."
and enter: ```/Library/Application Support/Colloquy/Styles```)
2. Right click "Succinct.colloquyStyle" and select "Show Package Contents."
3. Navigate to Contents -> Resources.
4. To change colors in the default theme, edit Main.css. To change Solarized colors, double click
the folder labeled "Variants."
5. The CSS files inside this folder are clearly labeled and ready to edit.

I used [this website](https://www.w3schools.com/colors/colors_picker.asp) to pick colors, very helpful. To view the changes you make in Colloquy, simply type ```/reload style```.

----------------

Contributors
------------

* Claudio Perez Gamayo <http://80kv.com>: Created first-draft design based on 37
  Signal's Campfire web application.
* Joel Watson <https://github.com/watsonian>
* John Albin <https://github.com/JohnAlbin>
* Willa Riggins <https://github.com/willasaywhat>

Additional bugfixes, usability improvements, and design comments are welcome!
Just use GitHub to fork and make pull requests.

Forked from John Albin's original: <https://github.com/JohnAlbin/succinct-for-colloquy>