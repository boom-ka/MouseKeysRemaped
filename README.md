AutoHotkey Mouse Remap

This script remaps the XButton2 (typically the "forward" button on a mouse) to function as the Left Mouse Button.

Script
XButton2::LButton

Requirements

AutoHotkey
 installed on Windows.

Setup

Install AutoHotkey.

Save the script above in a file named mouse_remap.ahk.

Double-click the file to run it.

The script will now make XButton2 act like the left mouse button.

Run at Startup

To make the script run automatically every time you start your computer:

Press Win + R, type:

shell:startup


and press Enter. This opens the Startup folder.

Place a shortcut to your mouse_remap.ahk file inside this folder.

Alternatively, place a shortcut to the compiled .exe if you convert your script with AutoHotkey.

Now, the script will run automatically when you log into Windows.

Notes

To stop the script, find the green "H" AutoHotkey icon in the system tray, right-click, and choose Exit.

You can edit the .ahk file to change the key/button mappings as needed.
