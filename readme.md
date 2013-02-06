Vintage Origami
===============

Origami is an awesome Sublime Text plugin that lets you conveniently configure your panel layout using shortcut keys.

Vintage Origami is just a bunch of additional shortcut keys for Vintage users so that the use of arrow keys can be avoided and `j`,`k`,`h`,`l` can be used instead.

Caveats
-------

* These bindings are only available in command mode (not insert mode).

* Instead of using `super+k` as the primary shortcut key, we have to use `super+j` instead. E.g.: `super+j j` would be equivalent to `super+k arrow-down`. The reason is to prevent conflicts with built-in default bindings (`super+k super+k` and `super+k super+j` are already assigned to some commands by default ).

So, to use this with Vintage, first press `super+j`, then press one of the `j k l h` keys with modifiers:

* no modifiers: travel to an adjacent pane
* `shift`: carry the current file to the destination
* `alt`(`option`):  clone the current file to the destination
* `super`: create an adjacent pane
* `super+shift`: destroy an adjacent pane

(Note: Windows and Linux use `ctrl` instead of `super`.)

Install
-------

Make sure you have Origami installed already:

	https://github.com/SublimeText/Origami

Vintage Origami is available through Package Control, which is available here:

    http://wbond.net/sublime_packages/package_control

Manual Install
--------------

First make sure Origami is already installed:

	https://github.com/SublimeText/Origami

Go to your Packages subdirectory under ST2's data directory:

* Windows: %APPDATA%\Sublime Text 2
* OS X: ~/Library/Application Support/Sublime Text 2
* Linux: ~/.config/sublime-text-2
* Portable Installation: Sublime Text 2/Data

Then clone this repository:

    git clone https://github.com/garyc40/Vintage-Origami.git

That's it!