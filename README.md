# CommandTerminal
Rainmeter skin for a custom command terminal on the desktop.

# Usage:
Install using the rmskin package. Next, goto the @Resources/Commands folder.

You then need to add a program shortcut e.g. I right click firefox go "Create Shortcut" and rename to "firefox.lnk"
Then copy to the @Resources/Commands folder and create a .bat file with the following arguments:

google.bat
```
START "" firefox.lnk https://www.google.com
```

That will open firefox at googles homepage. Then in the skin you type in "google" and it will execute google.bat, which then runs firefox.

The skin comes with google.bat already, you just need to provide the program shortcut "firefox.lnk".

Basically add a shortcut to the folder, then a batch file with:
```
START "" <SHORTCUT NAME>.lnk <ANY PARAMATERS HERE>
```
