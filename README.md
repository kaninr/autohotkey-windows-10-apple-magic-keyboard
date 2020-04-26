# autohotkey-windows-10-apple-magic-keyboard
AutoHotKey script that allows you to use an Apple Magic Keyboard in Windows 10 with Apple familiar keyboard shortcuts.

This is a very nice tool to have if like me you use an Apple Magic Keyboard and regularly switch between Windows and Mac. Now you can use the same familiar key combinations in both operating systems.

1. Install [AutoHotKey](https://autohotkey.com/download/)
2. Download and install the script file and open it
3. Enjoy using key combos such as Command + C to instead of Control + C to copy, and Command + Q instead of Alt + F4 to terminate the currently running app.

# How do I put my hotkeys and hotstrings into effect automatically every time I start my PC?
https://www.autohotkey.com/docs/FAQ.htm

There are several ways to make a script (or any program) launch automatically every time you start your PC. The easiest is to place a shortcut to the script in the Startup folder:

Find the script file, select it, and press Control+C.
Press Win+R to open the Run dialog, then enter shell:startup and click OK or Enter. This will open the Startup folder for the current user. To instead open the folder for all users, enter shell:common startup (however, in that case you must be an administrator to proceed).
Right click inside the window, and click "Paste Shortcut". The shortcut to the script should now be in the Startup folder.
