# Nautilus Git GUI

Nautilus Git GUI is extension for Nautilus which is default GNOME file manager.
This extension make it easy to access `git-gui` and `gitk` commands in the current directory.

Nautilus Git GUI adds the following items to the application menu when right click in an empty place.

* `[Git GUI Here]`: run `git gui` command in current direcotry.
* `[Gitk Here]`: run `gitk` command in current directory.


## Screenshot
![Application menu](./img/application-menu.jpg)

![git-gui](./img/git-gui.jpg)
![gitk](./img/gitk.jpg)


## Installation
1. Put or symlink `nautilus-git-gui.py` to  `$HOME/.local/share/nautilus-python/extensions/`. If you want to install it for all users, put it to `/usr/share/nautilus-python/extensions/`.

2. Restart nautilus.
```
nautilus -q
nautilus &
```


## Uninstallation
Delete `nautilus-git-gui.py` and `nautilus-git-gui.pyc` in following directory.
* `$HOME/.local/share/nautilus-python/extensions/`
* `/usr/share/nautilus-python/extensions/`


## Dependency
* Git
* GTK+
* Nautilus
* nautilus-python
* Python


## Attribution
* Author: SENOO, Ken
* License: CC0
