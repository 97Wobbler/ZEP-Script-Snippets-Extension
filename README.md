# ZEP Script Snippets

**ZEP Script** is a scripting language for creating an app that runs in **ZEP**, a 2D top-down metaverse platfrom.<br>
For more information about ZEP, visit the [official website of ZEP](https://zep.us/home/landing).

## NOTES

* This is **NOT** an official extension from ZEP, and is not endorsed or supported by ZEP.
* Information provided may **NOT** be complete, correct, or up-to-date.
* Only supports JavaScript documentation.

## Features

This extension generates snippets for writing ZEP Script.

* It auto-completes most of the methods and fields for the four classes in ZEP Script: ScriptApp, ScriptMap, ScriptPlayer, and ScriptWidget.
* It also auto-completes commonly used phrases and functions of ZEP Script, such as initializing a player's tag, saving a player's tag, and creating a loop for all players. <br>These can be accessed by typing keywords that start with 'ZS', such as 'ZSinitTag', 'ZSsaveTag', and 'ZSforAllPlayers'.

## Requirements

- To use this extension, your document **must be written in JavaScript(*.js)**.

## Release Notes

### 0.0.1

* Initial release of "ZEP Script Snippets" extension.

### 0.0.2

* Fixed some typos.
* New snippets for new methods and fields.

    * player.hideBuyAlert
    * player.openWebLink
    * App.changeAttackSound

### 0.0.3

* Fixed some typos and syntax errors.
* Added new snippets that provide detailed explanations for methods and fields.<br>
To access these explanations, simply type "HELP-" before the method or field name.

    * e.g. Typing "HELP-App.onInit" will provide a detailed description of the "onInit" method in the ScriptApp class.
    * e.g. Typing "HELP-player.sendUpdated" will provide a detailed description of the "sendUpdated" method in the ScriptPlayer class.

## Credits

* [@97wobbler](https://github.com/97wobbler)