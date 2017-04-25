# Slate window management

Slate allows for window management and focus.
This repo contains Hyper key hack & my config :heart:

## Install
Install [Slate](https://github.com/jigish/slate)

`brew cask install slate`

The Hyper key is more tricky, as [Karabiner](https://pqrs.org/osx/karabiner/) does not work on macOS Sierra

[Karabiner-elements](https://github.com/tekezo/Karabiner-Elements) is the replacement, but the Hyper key feature hasn't been released yet, despite the [enthusiasm](https://github.com/tekezo/Karabiner-Elements/pull/170)

Compiled release can be found [here](https://github.com/Ragnar-Hardarson/dotfiles/releases/download/0.90.64/Karabiner-Elements-0.90.64.dmg)

## Configuration
Save Slate [config](https://github.com/Ragnar-Hardarson/dotfiles/blob/master/.slate) to root.

`wget -O ~/.slate https://raw.githubusercontent.com/Ragnar-Hardarson/dotfiles/master/.slate`

Open Karabiner-elements and map Caps lock to Hyper
![karabiner-elements-setup](https://cloud.githubusercontent.com/assets/22854722/25352900/d4da758c-292d-11e7-93c3-1a40ec4be93d.gif)

Alternatively edit the karabiner.config file to match https://github.com/Ragnar-Hardarson/dotfiles/blob/master/karabiner.json

`vim ~/.karabiner.d/configuration/karabiner.json`

Reload Slate
1. Click Slate in toolbar
2. Click 'Reload and Load Config'

Enjoy your keybindings
