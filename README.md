You can find there a fully customizable and minimalistic Anki template created using HTML / CSS. It offers you the basic functionality to feel your studies more comfortable and easier (sometimes)!

## Installation guide

First of all, you need to install the Anki addon called [1210908941](https://ankiweb.net/shared/info/1210908941). It is used to change your background with a custom image. There are some of them in the _/background_ directory.

Secondly, find front-imgs with back-imgs (they can be images or even gifs) for each note and move them to the _/media_ directory (their names must be started with an underline to prevent Anki from deleting them). After all preparations have been made, transfer the _/media_ folder to the absolute path _%appdata%\\Anki2\\(There is an username which has been written on the language set in Anki)\\collection.media_ (you can do that by pressing _Win + R_)

Finally, download _test.apkg_ template or make new on your own using resources at _/template_ and _/color\_schemes_ directories.<br/>
P.S.: The _/color\_schemes_ directory is used for themes' color schemes. Right now there are just two of them, you can use those presets or create something really special depending on your needs. It can be reached by changing _--c1_, _--c2_ and _--ext_ vars in the _:root_ class.

## Examples

### Purple and Pink

<img src="./assets/purple_pink.png" />

### Blue and Green

<img src="./assets/blue_green.png">

