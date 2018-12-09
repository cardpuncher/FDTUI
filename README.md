# FreeDOS TUI Shell

Text User Interface Shell for FreeDOS

![Screenshot](screenshot.png)

Copyright (C) 2018 Ercan Ersoy<br />
This program is licensed under GNU General Public License version 3.

This project includes FDOSTUI library. FDOSTUI has own licenses.<br />
This project includes Kitten library. Kitten has own license.

# Thanks

Thanks to Atnode for French translation.

Thanks to Eric Auer for Kitten library.

Thanks to Jim Hall for Kitten library.

Thanks to Mark Olesen for some code changes and FDOSTUI library.

Thanks to Tom Ehlert for Kitten library.

# Compile

This software should be compiled with Open Watcom.

# Contribute

If you want to contribute to this project, you can report possible bugs and
make a pull request to the FreeDOS TUI Shell repository.

# Changelog

## 0.3 (12-09-2018)

* Changed color theme.

* Changed bar menus.

* Changed language files.

* Deleted unneded line of "DOSSHELL.FR".

* Fixed "Show Archive Items" checkbox and fixed "Show Hidden Items" checkbox on file manager.

* Disabled ESC key.

* Changed directory tree.

* Fixed some typos.

* Fixed drivers listbox selecting with keyboard bug.

* Fixed item attributes not shown with changing drive and file manager opening.

* Splitted header files and source files.

* Fix help parameter.

* Changed header files extensions to ".hpp" from ".h".

* Replaced clearing screen to standard function of Open Watcom instead of CLS command.

* Added GNU GPL version 2 license information.

## 0.2 (09-24-2018)

* Disabled menuitem foreground color have changed to grey on "FDOSTUI.INI". But, it seems red. (Possible another bug.)

* Changed default is showing archive items to enabled and showing readonly items to enabled.

* Fixed popup input of run command not cancelling bug. Add pause to ending to running command.

* Fixed newline bug of some files.

## 0.1 (07-13-2018)

* Create first version.
