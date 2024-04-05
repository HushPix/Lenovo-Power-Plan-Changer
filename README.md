# Lenovo-Power-Plan-Changer
This script makes changing power profiles on Lenovo Ideapad laptops even simpler than it already is.
It is based on [this article](https://wiki.archlinux.org/title/Lenovo_IdeaPad_5_Pro_14ACN6) from the Arch Wiki.

### Compatibility

Lenovo laptop models it works on:
+ Lenovo Ideapad 5 Pro 14arh7.

If it works on other models, i encourage you to message me about it, so i can update the compatibility list

### Usage

It's very simple:

1. You download it.
2. You have to change its permissions to read and write.

```
chmod +rw power-plan-changer
```
3. Launch the script and pick your options.

   

_The script automatically adds a shortcut on your desktop so you won't have to find it and run it via console._

## Issues

There are certain issues that i know of and i might fix in the future, such as:
+ If you move the script to a new location, you have to delete the shortcut (It doesn't update)
+ It requires sudo for the commands to work (I'll try to make it more elegant in the future)
