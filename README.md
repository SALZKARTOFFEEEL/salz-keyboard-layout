# SALZ Keyboard Layout
The SKL features a variety of (Unicode) symbols while aiming to be as logical and easy to use as possible. It is based on the QWERTY layout.

## The Layout
A handy spreadsheet displaying the layout [can be found here](https://docs.google.com/spreadsheets/d/1oFvmKjmBZegqOSWev_tbju-E4FzEx2xZXkOKFecYGdI/view).

Here is a screenshot:
![An Image of the Layout](https://files.catbox.moe/ykdb3i.png)

## Explanation
My aim with this is to create a keyboard layout that has support for all Unicode symbols (among standard ASCII ones) that are used in everyday writing.  
Some might say that it is not required to use Unicode symbols at all in daily writing. I think otherwise.  
Even before creating this layout I have used those symbols through [AutoHotkey](https://autohotkey.com). That was a big pain but even that was okay, as long as I could use those symbols.  
Now, with the creation of SLK, this was made much easier. All the symbols I need are there, right on my keyboard!

Also, it's just a nice challenge to throw away your muscle memory and learn a new layout!

## Installation
Head over to the [Releases page of this project](https://github.com/SALZKARTOFFEEEL/salz-keyboard-layout/releases).
There you can download the latest version and find instructions on the installation process.

You can also build the layout yourself, of course. See section [Building](https://github.com/SALZKARTOFFEEEL/salz-keyboard-layout#building) on how to do that.

## Uninstallation
If you kept the installation files (the contents of `KBDSALZ.zip`), just launch `setup.exe` to uninstall the layout again.

If you lost the files, redownload them.

In the worst case-scenario, `setup.exe` fails to uninstall the layout or you cannot download it anymore, you need to uninstall the layout manually. The [next section](https://github.com/SALZKARTOFFEEEL/salz-keyboard-layout#manual-uninstallation) explains how to do that.

### Manual Uninstallation
This is only necessary in the worst-case scenario described above. If you just want to uninstall the layout, refer to the section above this one, called Uninstallation.

You need to remove 2 files to uninstall SKL.  
Both files are called `KBDSALZ.dll` and they are found in the directories `%WinDir%\System32` and `%WinDir%\SysWOW64`.  
(`%WinDir%` usually resolves to `C:\Windows`.)  
Delete them and the layout is uninstalled.  
You may need to restart your computer.

## Building
If you just want to use the keyboard layout and trust me on not infecting your computer with malware, just Install SKL normally. See section [Installation](https://github.com/SALZKARTOFFEEEL/salz-keyboard-layout#installation) for that.

To build SKL, follow these steps:
* First, clone this repository to your local computer or just download `KBDSALZ.klc`, as it is the only source file required.  
* Next, install the [Microsoft Keyboard Layout Creator v1.4](https://www.microsoft.com/download/details.aspx?id=22339) (MSKLC for short).
  * Be sure to install it in its default location, or at least its default drive. I've had trouble building when I installed it on a secondary drive.
* Now open up the `.klc` file with MSKLC.  
* Be sure to change the working directory; the built files, as well as any logs, will go into there!
* Go to the menu “Project” and choose “Build DLL and Setup Package”.

If you have done everything correctly, the build will succeed and a folder will appear with all the required files for installation.
