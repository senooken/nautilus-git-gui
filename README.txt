# Nautilus Git GUI

License: CC0

Nautilus Git GUI is extension for Nautilus which is default GNOME file manager.
This extension make us easy to access `git gui` and `gitk` command in current directory.

Nautilus Git GUI adds following menu to application menu when right click in empty place.
* [Open Git GUI]: run `git gui` command in current direcotry.
* [Open GiTk]: run `gitk` command in current directory.



## Installation
1. Put or symlink `naitilus-gitgui.py` to  `$HOME/.local/share/nautilus-python/extensions/`. If you want to install all users, put it to `/usr/share/nautilus-python/extensions/`.

2. Restart nautilus.
```
nautilus -q
nautilus &
```

## Dependency
* Git
* Python
* nautilus-python
