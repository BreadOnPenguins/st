## simple terminal
My very simple fork of st, comes with no guarantees or warranties <sub>(to be clear: this means things may not work as expected, or at all)</sub> :^)

## patches added
* alpha & changealpha (transparency)
* Xresources w/ reload signal (pywal takes priority)
* ligatures
* scrollback ringbuffer, with mouse

## other stuff
* If you aren't using ```~/.Xresources``` or [pywal](https://github.com/dylanaraps/pywal), default color palette is [Nord](https://www.nordtheme.com/).
* Read or change keybinds, default font/size, etc. in **config.h** - I'll update the man page at some point. Bindings are what you'd expect, besides:
  - ```alt + c``` & ```alt + v``` for copy-paste
  - ```alt + a``` & ```alt + s``` to increase and decrease alpha (transparency) respectively
  - ```alt + shift + k``` & ```alt + shift + j``` to increase and decrease font size, respectively

## how install pls?
```
git clone https://github.com/BreadOnPenguins/st
cd st
sudo make install
```
