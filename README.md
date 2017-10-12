
<table width='100%'>
    <tr>
        <td align='left' width='100%' colspan='2'>
            <strong>Sublime-WP-Customizer-Snippets</strong><br />
            Sublime Package of snippets for WordPress Customizer.
        </td>
    </tr>
    <tr>
        <td>
            A FOSS (Free & Open Source Software) project. Maintained by <a href='https://github.com/ahmadawais'>@AhmadAwais</a>.
        </td>
        <td align='center'>
            <a href='https://AhmadAwais.com/'>
                <img src='https://i.imgur.com/Asg4d3k.png' width='100' />
            </a>
        </td>
    </tr>
</table>

# Sublime-WP-Customizer

[![Sublime-WP-Customizer](https://img.shields.io/badge/%F0%9F%94%A5%20Support%20Sublime%20Customizer-%E2%93%A6-brightgreen.svg?style=flat-square)](https://pay.paddle.com/checkout/515568) [![GPL](https://img.shields.io/badge/License-GPL-lightgrey.svg?style=flat-square)](http://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html) [![Package Control](https://img.shields.io/packagecontrol/dt/WordPress%20Customizer.svg?style=flat-square&maxAge=3600)](https://packagecontrol.io/packages/WordPress%20Customizer) [![GitHub release](https://img.shields.io/github/release/ahmadawais/Sublime-WP-Customizer.svg?style=flat-square)](https://github.com/ahmadawais/Sublime-WP-Customizer/releases) [![](https://img.shields.io/wordpress/v/akismet.svg?maxAge=2592000&style=flat-square&label=WordPress)](https://github.com/ahmadawais/Sublime-WP-Customizer/) [![](https://img.shields.io/github/stars/ahmadawais/Sublime-WP-Customizer.svg?style=social&label=Star&maxAge=200&cache=buster)](https://github.com/ahmadawais/Sublime-WP-Customizer/stargazers)

![WP Customizer Snippets](https://raw.githubusercontent.com/ahmadawais/Sublime-WP-Customizer/master/the.gif)

Sublime snippets for WordPress Customizer. 


## General Information

```
WordPress Version: 4.6.0
Snippets: 09
Version: 1.0.4
```

## Snippets

1. Snippet: WP Customize Add Pannel 
    * Tab trigger: `wpCustomizerAddPanel`
2. Snippet: WP Customize Add Section 
    * Tab trigger: `wpCustomizerAddSection`
3. Snippet: WP Customize Add Setting 
    *   Tab trigger: `wpCustomizerAddSetting`
4. Snippet: WP Customize Add Control Basic 
    * Tab trigger: `wpCustomizerAddControlBasic`
5. Snippet: WP Customize Add Control Image 
    * Tab trigger: `wpCustomizerAddControlImage`
6. Snippet: WP Customize Add Control Upload 
    * Tab trigger: `wpCustomizerAddControlUpload`
7. Snippet: WP Customize Add Control Color 
    * Tab trigger: `wpCustomizerAddControlColor`
8. Snippet: WP Customize postMessage JS Basic 
    * Tab trigger: `wpCustomizerPostMessageJSBasic`
9. Snippet: WP Customize Register Function
    * Tab trigger: `wpCustomizerRegisterFunction`


### Tab Triggers

You can do a fuzzy search inside PHP or JS file with initials of the snippets' names. E.g. To add a `WP Customizer Add Pannel` you can just type `wpcap` and Sublime will suggest the snippet. If that doesn't happen read the optional tip below. You can also open Package Control's Command Pallet: <kbd>Command</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> on Mac <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> on Windows or Linux and search for these snippets.

### How to Use the Snippets?

WP Customize snippets are meant to bring ease to your workflow. All you have to do is select a snippet and then press <kbd>Tab</kbd> button to go from one editable area to another. E.g.

![WP Customizer Snippets](https://raw.githubusercontent.com/ahmadawais/Sublime-WP-Customizer/master/the.gif)

### Optional Tip

Sublime won't autocomplete PHP files when there is no closing `?>` tags , so go to `Sublime Text > Preferences > Settings-User` add this snippet:

```bash
"auto_complete_selector": "source, text",
```

## Install Instructions

### Package Control installation

The preferred method of installation is via Package Control.

1. [Install Package Control](https://packagecontrol.io/installation).
2. From inside the Sublime Text, open Package Control's Command Pallet: <kbd>Command</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> on Mac <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> on Windows or Linux.
3. Type `Install Package` and hit <kbd>Return</kbd> or <kbd>Enter</kbd>. A list of available packages will be displayed.
4. Type `WordPress Customizer` and hit <kbd>Return</kbd> or <kbd>Enter</kbd>. The package will be downloaded to the appropriate directory (You can watch the progress bar in the left bottom bar of Sublime).
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

#### **OSX Macbook**

- Sublime Text 2 `/Users/{user}/Library/Application Support/Sublime Text 2/Packages`
- Sublime Text 3 `/Users/{user}/Library/Application Support/Sublime Text 3/Packages`

#### **WINDOWS**

- Sublime Text 2 `C:\Users\%username%\AppData\Roaming\Sublime Text 2\Packages`
- Sublime Text 3 `C:\Users\%username%\AppData\Roaming\Sublime Text 3\Packages`

### Changelog

#### Version 1.0.4

- UPDATE: ReadMe updated
- FIX: Add Section Tab trigger

#### Version 1.0.3

- UPDATE: ReadMe updated
- NEW: Package Control Messages

#### Version 1.0.2

- ReadMe updated
- Small Snippet bug fixes in WP Customize Register Function 

#### Version 1.0.1

- Package Control Support
- New Snippet: WP Customize Register Function 

#### Version 1.0.0

- First version
- Snippets 8

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

---
### 🙌 [WPCOUPLE PARTNERS](https://WPCouple.com/partners):
This open source project is maintained by the help of awesome businesses listed below. What? [Read more about it →](https://WPCouple.com/partners)

<table width='100%'>
	<tr>
		<td width='333.33'><a target='_blank' href='https://www.gravityforms.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtrE/c' /></a></td>
		<td width='333.33'><a target='_blank' href='https://kinsta.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mu5O/c' /></a></td>
		<td width='333.33'><a target='_blank' href='https://wpengine.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mto3/c' /></a></td>
	</tr>
	<tr>
		<td width='333.33'><a target='_blank' href='https://www.sitelock.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtyZ/c' /></a></td>
		<td width='333.33'><a target='_blank' href='https://wp-rocket.me/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtrv/c' /></a></td>
		<td width='333.33'><a target='_blank' href='https://blogvault.net/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtph/c' /></a></td>
	</tr>
	<tr>
		<td width='333.33'><a target='_blank' href='http://cridio.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtmy/c' /></a></td>
		<td width='333.33'><a target='_blank' href='http://wecobble.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtrW/c' /></a></td>
		<td width='333.33'><a target='_blank' href='https://www.cloudways.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mu0C/c' /></a></td>
	</tr>
	<tr>
		<td width='333.33'><a target='_blank' href='https://www.cozmoslabs.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mu9W/c' /></a></td>
		<td width='333.33'><a target='_blank' href='https://wpgeodirectory.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtwv/c' /></a></td>
		<td width='333.33'><a target='_blank' href='https://www.wpsecurityauditlog.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtkh/c' /></a></td>
	</tr>
	<tr>
		<td width='333.33'><a target='_blank' href='https://mythemeshop.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/n3ug/c' /></a></td>
		<td width='333.33'><a target='_blank' href='https://www.liquidweb.com/?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mtnt/c' /></a></td>
		<td width='333.33'><a target='_blank' href='https://WPCouple.com/contact?utm_source=WPCouple&utm_medium=Partner'><img src='http://on.ahmda.ws/mu3F/c' /></a></td>
	</tr>
</table>
