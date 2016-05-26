# Sublime-WP-Customizer
Sublime snippets for WordPress Customizer. 

## General Information
```
WordPress Version: 4.6.0
Snippets: 9
```

## Snippets
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

##Install Instructions
Sooner than later these snippets will be available via package control (WordPress Customizer) right now you can clone this repository into your Sublime Text `Packages` directory. Get to it quickly from within Sublime via the menu at `Sublime Text > Preferences > Browse Packages`.

So, browse the `Packages` directory in terminal and clone this repository inside it by running the following command.

```bash
$ git clone https://github.com/ahmadawais/Sublime-WP-Customizer.git WP-Customizer
```

`Packages` directory can be found in 
**OSX Macbook**
- Sublime Text 2 `/Users/{user}/Library/Application Support/Sublime Text 2/Packages`
- Sublime Text 3 `/Users/{user}/Library/Application Support/Sublime Text 3/Packages`

**WINDOWS**
- Sublime Text 2 `C:\Users\%username%\AppData\Roaming\Sublime Text 2\Packages`
- Sublime Text 3 `C:\Users\%username%\AppData\Roaming\Sublime Text 3\Packages`


### Optional Tip

Sublime won't autocomplete PHP files when there is no closing `?>` tags , so go to `Sublime Text > Preferences > Settings-User` add this snippet:

```
"auto_complete_selector": "source, text",
```
