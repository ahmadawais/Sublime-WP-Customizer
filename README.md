# Sublime-WP-Customizer

Sublime snippets for WordPress Customizer. 

## General Information

```
WordPress Version: 4.6.0
Snippets: 09
```

## Snippets

To make the snippets unique, this package uses `np` prefix which is the fuzzy search for `Snippet`.

- Snippet: WP Customize Add Pannel `Tab trigger: npwpcapannel`
- Snippet: WP Customize Add Section `Tab trigger: npwpcasection`
- Snippet: WP Customize Add Setting `Tab trigger: npwpcaseting`
- Snippet: WP Customize Add Control Basic `Tab trigger: npwpcacontrolbasic`
- Snippet: WP Customize Add Control Image `Tab trigger: npwpcacontrolimage`
- Snippet: WP Customize Add Control Upload `Tab trigger: npwpcacontrolupload`
- Snippet: WP Customize Add Control Color `Tab trigger: npwpcacontrolcolor`
- Snippet: WP Customize postMessage JS Basic `Tab trigger: npwpcpostMessageJSBasic`

### Tab Triggers

You can do a fuzzy search inside PHP or JS file with initials of the snippets' names. E.g. To add a `WP Customizer Add Pannel` you can just type `npwpcap` and Sublime will suggest the snippet.

### How to use the snippets?

WP Customize snippets are meant to bring ease to your workflow. All you have to do is select a snippet and then press `tab` button to go from one editable area to another. E.g.

![WP Customizer Snippets](https://i.imgur.com/nmNhiiF.gif)

### Optional Tip

Sublime won't autocomplete PHP files when there is no closing `?>` tags , so go to `Sublime Text > Preferences > Settings-User` add this snippet:

```bash
"auto_complete_selector": "source, text",
```

##Install Instructions

###Package Control installation

The preferred method of installation is via Package Control.

1. [Install Package Control](https://packagecontrol.io/installation).
2. From inside the Sublime Text, open Package Control's Command Pallet: `Command+Shift+P`  on Mac `Ctrl+Shift+P` on Windows or Linux.
3. Type `Install Package` and hit `Return or Enter`. A list of available packages will be displayed.
4. Type `WordPress Customizer` and hit `Return or Enter`. The package will be downloaded to the appropriate directory (You can watch the progress bar in the left bottom bar of Sublime).
5. Restart Sublime Text to complete installation. The features listed above should now be available.


### Manual Installation

1. Close Sublime Text.
2. Download or clone this repository to a directory named `WordPress-Customizer` in the Sublime Text Packages directory for your platform:
    * Sublime Text 3
        - **OS X**: `git clone https://github.com/ahmadawais/Sublime-WP-Customizer.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/WordPress-Customizer`
        - **Windows**: `git clone https://github.com/ahmadawais/Sublime-WP-Customizer.git %APPDATA%\Sublime/ Text/ 3/Packages/WordPress-Customizer`
        - **Linux**: `git clone https://github.com/ahmadawais/Sublime-WP-Customizer.git ~/.config/sublime-text-3/Packages/WordPress-Customizer`
    * Sublime Text 2
        - **OS X**: `git clone https://github.com/ahmadawais/Sublime-WP-Customizer.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/WordPress-Customizer`
        - **Windows**: `git clone https://github.com/ahmadawais/Sublime-WP-Customizer.git %APPDATA%\Sublime/ Text/ 2/Packages/WordPress-Customizer`
        - **Linux**: `git clone https://github.com/ahmadawais/Sublime-WP-Customizer.git ~/.config/sublime-text-2/Packages/WordPress-Customizer`
3. Restart Sublime Text to complete installation. The features listed above should now be available.

### Understand manual installation.
You can manually install by cloning this repository into your Sublime Text `Packages` directory. Get to it quickly from within Sublime via the menu at `Sublime Text > Preferences > Browse Packages`.
So, browse the `Packages` directory in terminal and clone this repository inside it by running the following command.

```bash
$ git clone https://github.com/ahmadawais/Sublime-WP-Customizer.git WP-Customizer
```

`Packages` directory can be found in 

####**OSX Macbook**

- Sublime Text 2 `/Users/{user}/Library/Application Support/Sublime Text 2/Packages`
- Sublime Text 3 `/Users/{user}/Library/Application Support/Sublime Text 3/Packages`

####**WINDOWS**

- Sublime Text 2 `C:\Users\%username%\AppData\Roaming\Sublime Text 2\Packages`
- Sublime Text 3 `C:\Users\%username%\AppData\Roaming\Sublime Text 3\Packages`


### License & Copyright

GPL v2.0 or later.
Copyright (C) 2016  Ahmad Awais http://AhmadAwais.com/

This program is free software; you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the Free
Software Foundation; either version 2 of the License, or (at your option)
any later version.

This program is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or
FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for
more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
