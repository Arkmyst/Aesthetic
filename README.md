## 💻 Overview

This homepage is built on top of the [tartarus-startpage] which itself is inspired by [dawn], which has further functionality. I've made slight adjustments to the page's aesthetics to align with the style  of [catppuccin], similar to that which is seen in [catppuccin-startpage]. Nevertheless, this repository is to further personalize it according to my own preferences.


## ⌨️ Keybindings
| Hotkey                                            | Action                      |
| ------------------------------------------------- | --------------------------- |
| <kbd>Numrow</kbd> \| <kbd>MouseWheel</kbd> \| <kbd>Click</kbd> | Switch tabs            |
| <kbd>s</kbd>                           | Search Dialog            |
| <kbd>q</kbd>                           | Config Dialog (new)           |
| <kbd>Esc</kbd>                           | Close Dialogs            |

## ⚙️ Configuration Dialog
![config-dialog](https://github.com/AllJavi/tartarus-startpage/assets/49349604/3b42c650-b5bb-4a7d-a358-cfa5a8915966)

The default configuration file is [userconfig.js](userconfig.js), but you can change it in the configuration dialog. You can find more information about how the file works in the [original repository](https://github.com/b-coimbra/dawn). The available components are tabs, a clock, and weather.

Additionally, there are two different new options:
- `fastlink`: To set the link of the Pokeball button.
- `localIcons`: To optimize the loading time of the icons, you can check it out [here](#local-icons).

## 🔍 Search Dialog
![search-dialog](https://github.com/AllJavi/tartarus-startpage/assets/49349604/3f76323d-88c4-41b6-b93d-e4cceb1780b7)

The search dialog allows you to display a search bar with various search engines defined in the configuration. To select each one, you simply need to prefix the query with the corresponding `!<id>`.
By default, the defined search engines are:
- `!g`: google
- `!d`: duckduckgo
- `!y`: youtube
- `!r`: reddit
- `!p`: pinterest

## 🖼 Available banners
|cbg-2|cbg-3|cbg-4|cbg-5|
| ------------- | ------------- | ------------- | ------------- | 
|<img src="src/img/banners/cbg-2.gif" width=175>|<img src="src/img/banners/cbg-3.gif" width=175>|<img src="src/img/banners/cbg-4.gif" width=175>|<img src="src/img/banners/cbg-5.gif" width=175>|

|cbg-6|cbg-7|cbg-8|cbg-9|
| ------------- | ------------- | ------------- | ------------- |
|<img src="src/img/banners/cbg-6.gif" width=175>|<img src="src/img/banners/cbg-7.gif" width=175>|<img src="src/img/banners/cbg-8.gif" width=175>|<img src="src/img/banners/cbg-9.gif" width=175>|

|cbg-10|cbg-11|cbg-12|cbg-13|
| ------------- | ------------- | ------------- | ------------- |
|<img src="src/img/banners/cbg-10.gif" width=175>|<img src="src/img/banners/cbg-11.gif" width=175>|<img src="src/img/banners/cbg-12.gif" width=175>|<img src="src/img/banners/cbg-13.gif" width=175>|

## Local Icons
If you want to reduce the loading time of the icons, you could install the [icon font](https://github.com/AllJavi/tartarus-startpage/tree/master/src/fonts) locally and activate the option `"localIcons": true` in the config to disable the remote styles.

## Credit
- [Dawn Startpage](https://github.com/b-coimbra/dawn) ([preview](https://startpage.metaphoric.dev/))
- [Tartarus Startpage](https://github.com/AllJavi/tartarus-startpage) ([preview](https://alljavi.github.io/tartarus-startpage/))
- [Catppuccin Startpage](https://github.com/volopivoshenko/catppuccin-startpage) ([preview](https://volopivoshenko.github.io/catppuccin-startpage/))

[dawn]: https://github.com/b-coimbra/dawn
[tartarus-startpage]:https://github.com/AllJavi/tartarus-startpage
[catppuccin-startpage]:https://github.com/volopivoshenko/catppuccin-startpage
[catppuccin]: https://github.com/catppuccin/catppuccin
