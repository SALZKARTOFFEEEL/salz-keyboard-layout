# SALZ Keyboard Layout
The SKL features a variety of (Unicode) symbols while aiming to be as logical and easy to use as possible. It is based on the QWERTY layout.

## The Layout
A handy spreadsheet displaying the layout [can be found here](https://docs.google.com/spreadsheets/d/1oFvmKjmBZegqOSWev_tbju-E4FzEx2xZXkOKFecYGdI/view).

## Explanation
My aim with this is to create a keyboard layout that has support for all Unicode symbols (among standard ASCII ones) that are used in everyday writing.  
Some might say that it is not required to use Unicode symbols at all in daily writing. I think otherwise.  
Even before creating this layout I have used those symbols through [AutoHotkey](https://autohotkey.com). That was a big pain but even that was okay, as long as I could use those symbols.  
Now, with the creation of SLK, this was made much easier. All the symbols I need are there, right on my keyboard!

Also, it's just a nice challenge to throw away your muscle memory and learn a new layout!

## Installation
Head over to the [Releases page of this project](https://github.com/SALZKARTOFFEEEL/salz-keyboard-layout/releases).
There you can download the latest version and find instructions on the installation process.

## Uninstallation
If you kept the installation files (the contents of `KBDSALZ.zip`), just launch `setup.exe` to uninstall the layout again.  
If you lost the files, redownload them.

In the worst case-scenario that (whatever reason) `setup.exe` fails to uninstall or you cannot download it anymore, you need to uninstall the layout manually.

### Manual Uninstallation
This is only necessary in the worst-case scenario described above. If you just want to uninstall the layout, refer to the section above this one, called Uninstallation.

You need to remove 2 files to uninstall SKL.  
Both files are called `KBDSALZ.dll` and they are found in the directories `%WinDir%\System32` and `%WinDir%\SysWOW64`.  
(`%WinDir%` usually resolves to `C:\Windows`.)  
Delete them and the layout is uninstalled.  
You may need to restart your computer.
