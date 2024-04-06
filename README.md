# Terminal

<img src="screenshot-1.gif" width="192">
<img src="screenshot-2.gif" width="192">

Featuring a command prompt user interface, this program has many useful commands and program management features. Some of the more significant functions include checking the battery status, turning TI-OS lowercase on/off, listing all the programs and appvariables on the device (including hidden files), and seeing how much storage is being used. Terminal can also be used as a full program manager, and can lock, hide, archive, run and delete programs.

## Platform

This program was built for the Texas Instruments 83+/84 graphing calculator (black and white edition). It was made with [Axe Parser](https://www.ticalc.org/archives/files/fileinfo/456/45659.html), a low-level language syntactically similar to TI-BASIC but compiled into much faster binaries with graphics, grayscale support, multiplayer functionality, and more.

## Download

* Terminal  
https://github.com/scottmangiapane/ti-terminal/blob/master/terminal.8xk

## How to Install

* Download TI Connect  
https://education.ti.com/en/us/software/search/ti-83-plus-family
* Connect your TI-83+ or TI-84 to the computer
* Transfer 'terminal.8xk' to the device using TI Connect
* Run the program from the [APPS] menu

## How To Use

* `[2ND]` allows the user to type numbers
* `[ALPHA]` allows the user to type letters
* `[ENTER]` runs whatever command is typed
* `[MODE]` automatically types the EXIT command
* `[CLEAR]` automatically types the CLEAR command
* `[ON]` automatically types the OFF command

## Command List

**Standard Commands**

* `AUTO-CASE-ON` automatically runs CASE-ON whenever the terminal starts
* `AUTO-CASE-OFF` disables AUTO-CASE
* `BATTERY` shows the battery status as a fraction
* `CASE-ON` allows the user to type lowercase letters throughout the operating system by pressing [ALPHA] twice
* `CASE-OFF` disables TI-OS lowercase
* `CLEAR` clears the screen
* `EXIT` exits the terminal
* `HISTORY-ON` keeps commands visible after they are executed
* `HISTORY-OFF` hides previous commands to make the display less cluttered
* `INFO` displays information about Terminal
* `INVERT` will invert the display
* `LIST-APPV` lists all the app variables found on the device (run as root to see hidden app variables)
* `LIST-PRGM` lists programs found on the device, including hidden programs (programs that do not start with a letter or number are excluded, such as prgm! and DoorsCS folders)
* `OFF` will put the device to sleep without exiting the terminal
* `RAM` displays the available RAM
* `ROM` displays the available and total storage

**PRGM Commands**

* `PRGM` allows the user to select a program and enter program manager mode, enabling the following commands
* `LOCK` locks the selected program
* `UNLOCK` unlocks the selected program
* `HIDE` hides the selected program
* `UNHIDE` unhides the selected program
* `ARCHIVE` archives the selected program
* `UNARCHIVE` unarchives the selected program
* `RUN` runs the selected program (assembly only)
* `DEL` deletes the selected program
* `EXIT` returns to the standard terminal

**SUDO Commands**

* `SUDO` enables root access, giving the user access to all root commands
* `AUTO-LOCK-ON` (root only) Makes root access required to run any commands
* `AUTO-LOCK-OFF` (root only) Disables auto lock
* `KILL` (root only) freezes the calculator by corrupting the archive  
WARNING! This command is very dangerous. It will corrupt the device's archive, which is difficult to fix without resetting the device (full reset, not a RAM clear).
* `EXIT` returns to the standard terminal

## Special Thanks

Special thanks to [Kevin Horowitz](https://www.ticalc.org/archives/files/authors/103/10304.html) for his work on [Axe Parser](https://www.ticalc.org/archives/files/fileinfo/456/45659.html) and [Brian Coventry](https://github.com/bcov77) for his work on [zStart](https://www.omnimaga.org/ti-z80-calculator-projects/zstart-an-app-that-runs-on-ram-clears/msg361451/#msg361451), without which this wouldn't be possible.
