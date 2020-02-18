# SALZ Keyboard Layout
The SKL features a variety of (Unicode) symbols while aiming to be as logical and easy to use as possible. It is based on the QWERTY layout.

## The Layout
A handy spreadsheet displaying the layout [can be found here](https://docs.google.com/spreadsheets/d/1oFvmKjmBZegqOSWev_tbju-E4FzEx2xZXkOKFecYGdI/view).

Here is a screenshot:
![An Image of the Layout](https://files.catbox.moe/eyunn8.png)

## Explanation
My aim with this is to create a keyboard layout that has support for all Unicode symbols (among standard ASCII ones) that are used in everyday writing.  
Some might say that it is not required to use Unicode symbols at all in daily writing; I say otherwise.  
Even before creating this layout I have used those symbols through [AutoHotkey](https://autohotkey.com). It was a big pain but even that was okay, as long as I could use those symbols.  
Now, with the creation of SKL, this was made much easier. All the symbols I need are there, right on my keyboard!

Also, it's just a nice challenge to throw out your muscle memory and learn a new layout!

## Installation – Linux (xkb)
* Clone or download the contents of the repository to your system.
    * You will only need the files `salz` and `evdev.xml`.
* Copy `salz` into `/usr/share/X11/xkb/symbols`.
* Put the `<layout>` tag in `evdev.xml` into `/usr/share/X11/xkb/rules/evdev.xml`'s `<layoutList>` tag.
* Restart the X server (log out and back in) and select SKL as your keyboard layout.

## Uninstallation
Refer to [the section above](#installation--linux-xkb) to know which files and changes I'm talking about.

* Delete `/usr/share/X11/xkb/symbols/salz`.
* Undo the changes made to `/usr/share/X11/xkb/rules/evdev.xml` during the installation.

## Note
This is the Linux version of SKL.
The Windows versions sits at the master branch of this repository.
