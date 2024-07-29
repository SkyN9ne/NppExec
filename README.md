# NppExec (Notepad++ Console)

### Summary about NppExec

* NppExec adds a Console window at the bottom of Notepad++'s window;
This Console window allows to run different console programs directly in it;
Also there is Plugins -> NppExec -> Execute... window that allows to execute NppExec's scripts (set of commands).
* NppExec's commands and variables are listed in the `NppExec.txt` file.
* To get more details, type `help` directly in NppExec's Console.
* To get detailed help about any of NppExec's commands, type `help [command]` - for example `help npp_open` or `help set`
* There is also Plugins -> NppExec -> Help/Manual.

## Installation:

* Just unzip the `NppExec.zip` archive (the last `*_.dll.zip` from either [https://github.com/d0vgan/nppexec/releases](https://github.com/d0vgan/nppexec/releases) or [https://sourceforge.net/projects/npp-plugins/files/NppExec](https://sourceforge.net/projects/npp-plugins/files/NppExec) to the `Notepad++\plugins\` directory (typically under either `%ProgramFiles%` or `%APPDATA%`) It will extract the file `NppExec.dll` as well as the `doc\NppExec\` and `NppExec\` subfolders (the latter one contains header files used by NppExec at runtime).
* The only difference between the `*.dll.zip` and `*.dll_PA.zip` is the plugin folder structure. The `*.dll.zip` corresponds to the plugin folder structure prior to Notepad++ v 7.6.*, whereas the `*.dll_PA.zip` follows the new plugin folder structure introduced in Notepad++ v7.6+ together with the Plugins Admin.

## Note:
If you see just blank pages inside the NppExec Manual or see messages similar to `This web content was blocked` or `This web page could not be shown`, and want to unblock them read:
* Unblocking `.CHM` files: <https://stackoverflow.com/questions/4400744/chm-viewer-unable-to-show-contents>
* And also: <https://stackoverflow.com/questions/11438634/opening-a-chm-file-produces-navigation-to-the-webpage-was-canceled>
* Unblocking `.CHM` files for Windows 7 and above: <https://support.microsoft.com/kb/2021383>

### Now there's a web version of the NppExec Manual: 
[https://d0vgan.github.io/nppexec](https://d0vgan.github.io/nppexec)

* You could still save it locally by downloading it with `wget` or `curl` or even PowerShell
