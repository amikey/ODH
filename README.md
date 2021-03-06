# Online Dictionary Helper (with Anki app support)

[[中文版说明](README.zh_CN.md)]

Online Dictionary Helper is a chrome extension to show online dictionary content, which also supports flash-card making compatible with Anki  (with **ankiconnect**, an Anki add-on, installed).

For the reason why comes this extension, you may check the detail [background](doc/background.md) if you are interested.

![Anki Notes](https://raw.githubusercontent.com/ninja33/ODH/master/doc/img/anki_001_640x400.png)

What might set this extension apart is that the users can grab online dictionary content with their own customized script (running under extension development mode). For development detail, please check the [development guide](doc/development.md)

## How to use

[[Chrome Web Store Link](https://chrome.google.com/webstore/detail/anki-online-dictionary-he/lppjdajkacanlmpbbcdkccjkdbpllajb?hl=en)]

1. Install the extension first from Chrome Web store. Setup Option and turn on the extension if you want. (Details could be found under the option page section)
2. Open any given web page, move mouse cursor to the word.
3. Click-drag/Double click to select word, or press **Hotkey**(defined in options page) to automatically select word in case it's a link.
4. A popup window will show up displaying the word definition.
5. (Optional) Setup the designated Anki deck, type and fields names to put your **word**, **definition**, **sentence** while Anki and ankiconnect is running.
6. (Optional) Press top/right green **(+)** icon in popup window to add Anki note.

## The Option Page

The extension option page is divided in three sections.

1. General Option: Turn on or turn off the extension if you want.
2. Anki Options: Setup Anki deck/type name, and which fields you are going to put **word**, **reading**, **extrainfo**, **definiton**, **sentence**.

3. Dictionary Options:

    - Dictioanry Scrip: Input your own script name here, and click <kbd>Load Script</kbd> button to load it.
    - Selected Dictionary: Here will display all available dictionaries (buildin or loaded), and please select what current dictionary you want to use.

![Options Page](https://raw.githubusercontent.com/ninja33/ODH/master/doc/img/option_general_640x400_en.png)

## Use existing script or develop by yourself

1. You can use exsiting dictionary scripts in the [dictionaries list](doc/scriptlist.md)
2. Or develop the script by yourself based on [development guide](doc/development.md) 
3. Or raise an [issue](https://github.com/ninja33/ODH/issues) here if you really need help.

## Pull request

Welcome pull request if you want to enhance this extension, or put your own script in next release.

- the exntension source will go to [/src](https://github.com/ninja33/ODH/tree/master/src)
- the dictionary script will go to [/src/bg/local](https://github.com/ninja33/ODH/tree/master/src/bg/local)
