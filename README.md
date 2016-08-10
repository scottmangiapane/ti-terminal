## Terminal

<img src="screenshot-1.gif" width="192">
<img src="screenshot-2.gif" width="192">

Featuring a command prompt user interface, this program has many useful commands and program management features. Some of the more significant functions include checking the battery status, turning TI-OS lowercase on/off, listing all the programs and appvariables on the device (including hidden files), and seeing how much space is used. Terminal can also be used as a full program manager, and can lock, hide, archive, run and delete programs.

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

Type commands with the keyboard and run them by pressing [ENTER]. Press [2ND] to type numbers and [ALPHA] to type letters.

## Command List

**Standard Commands**

<ul>
<li>"AUTO-CASE-ON" automatically runs CASE-ON whenever the terminal starts.</li>
<li>"AUTO-CASE-OFF" disables AUTO-CASE.</li>
<li>"BATTERY" shows the battery status as a fraction.</li>
<li>"CASE-ON" allows the user to type lowercase letters throughout the system by pressing [ALPHA] twice.</li>
<li>"CASE-OFF" disables TI-OS lowercase.</li>
<li>"CLEAR" clears the screen.</li>
<li>"EXIT" exits the terminal.</li>
<li>"HISTORY-ON" keeps commands visible after they are executed.</li>
<li>"HISTORY-OFF" hides previous commands to make the display less cluttered.</li>
<li>"INFO" displays information about Terminal.</li>
<li>"INVERT" will invert the display colors.</li>
<li>"LIST-APPV" lists all the app variables found on the device.</li>
<li>"LIST-PRGM" lists programs found on the device (programs that do not start with a letter or number are excluded, such as prgm!).</li>
<li>"OFF" will put the device to sleep without exiting the terminal.</li>
<li>"RAM" displays the available RAM.</li>
<li>"ROM" displays the available and total storage.</li>
</ul>

**PRGM Commands**
<ul>
<li>"PRGM" allows the user to select a program and enter program manager mode, enabling the following commands.</li>
<li>"LOCK" locks the selected program.</li>
<li>"UNLOCK" unlocks the selected program.</li>
<li>"HIDE" hides the selected program.</li>
<li>"UNHIDE" unhides the selected program.</li>
<li>"ARCHIVE" archives the selected program.</li>
<li>"UNARCHIVE" unarchives the selected program.</li>
<li>"RUN" runs the selected program (assembly only).</li>
<li>"DEL" deletes the selected program.</li>
<li>"EXIT" returns to the standard terminal.</li>
</ul>

**Sudo Commands**
<ul>
<li>"SUDO" enables root access, giving the user access to all root commands.</li>
<li>"AUTO-LOCK-ON" (root only) Makes root access required to run any commands.</li>
<li>"AUTO-LOCK-ON" (root only) Disables auto lock.</li>
<li>"KILL" (root only) WARNING! This command is very dangerous. It will corrupt your archive, which is difficult to fix without resetting the device. It is designed as a proof of concept command only, and only run it if you are okay with losing everything. I am not responsible for anything you do to your device.</li>
<li>"EXIT" returns to the standard terminal.</li>
</ul>
