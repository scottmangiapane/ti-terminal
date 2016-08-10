## Terminal

<img src="screenshot-1.gif" width="192">
<img src="screenshot-2.gif" width="192">

Featuring a command prompt user interface, this program has many useful commands and program management features. Some of the more significant abilities include checking the battery status, turning TI-OS lowercase on/off, listing all the programs and appvariables on the device (including hidden files), and returning ram info and archive info. Terminal can also lock, hide and archive programs.

## Platform

This program is built for the Texas Instruments 83+/84 graphing calculator (black and white edition).

## Download

<ul>
<li>Terminal<br>https://github.com/scottmangiapane/ti-terminal/blob/master/terminal.8xk</li>
</ul>

## How to Install

<ul>
<li>Download TI Connect<br>https://education.ti.com/en/us/software/search/ti-83-plus-family</li>
<li>Connect the TI-83+ or TI-84 to the computer</li>
<li>Transfer terminal.8xk to the device using TI Connect</li>
<li>Run the program from the [APPS] menu</li>
</ul>

## How To Use

Type a command using the keys, then submit the command by pressing [ENTER]. Press [2ND] to type numbers and press [ALPHA] to type letters.

## Command List

<ul>
<li>"PRGM" allows the user to type the name of the program on the next line. Type just the name of the program, so if you want to run a program called prgmTEST, then: type "PRGM", press ENTER, type "TEST", press ENTER, type "RUN", and press ENTER again.</li>
<li>"LOCK" locks the selected program.</li>
<li>"UNLOCK" unlocks the selected program.</li>
<li>"HIDE" hides the selected program.</li>
<li>"UNHIDE" unhides the selected program.</li>
<li>"ARCHIVE" archives the selected program.</li>
<li>"UNARCHIVE" unarchives the selected program.</li>
<li>"RUN" runs the selected program if it is ASM.</li>
<li>"DEL" deletes the selected program.</li>

<li>"AUTO-CASE-ON" (default) will make Terminal enable TI OS lowercase every time it is run.</li>
<li>"AUTO-CASE-OFF" will disable this feature.</li>
<li>"BATTERY" will show the battery status as either 100%, 75%, 50%, 25%, or 0%.</li>
<li>"CASE-ON" allow the user to type lowercase letters from the home screen by pressing [ALPHA] twice.</li>
<li>"CASE-OFF" will disable TI OS lowercase.</li>
<li>"CLEAR" clears the screen.</li>
<li>"EXIT" exits the program.</li>
<li>"HISTORY-ON" keeps commands visible after they have been executed (default).</li>
<li>"HISTORY-OFF" hides previous commands to make the display less cluttered.</li>
<li>"INFO" displays information about Terminal.</li>
<li>"INVERT" will invert the display colors.</li>
<li>"LIST-APPV" lists all the app-variables found on the calculator.</li>
<li>"LIST-PRGM" lists mosts programs found on the calculator (prgm! and prgm# are hidden, along with programs that do not start with a letter, number, or hidden programs such as doorscs folders).</li>
<li>"OFF" will turn off the device without exiting the terminal.</li>
<li>"RAM" displays the available RAM.</li>
<li>"ROM" displays the available / total archive memory.</li>

<li>"SUDO" enables root access, giving the user access to all root commands.</li>
<li>"AUTO-LOCK-ON" (root only) Makes root access required to run any commands.</li>
<li>"AUTO-LOCK-ON" (root only) Disables auto lock.</li>
<li>"KILL" (root only) WARNING! This command is very dangerous. It will corrupt your archive, which is difficult to fix without resetting the device. It is designed as a proof of concept command only, and only run it if you are okay with losing everything. I am not responsible for anything you do to your device.</li>
</ul>
