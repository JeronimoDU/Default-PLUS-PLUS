# Default-PLUS-PLUS v3.6 for release 1.4.2

Dual Univers most Advanced flight script

Default++ developed since 2017, is the most advanced and innovative flight script with a unique navigation operating system Winlib++.

DU flight parameters are brought to you to an other level with dozens and dozens of customizable settings.

![dualuniverse_2023-05-09_01h26m34s](https://user-images.githubusercontent.com/75027025/236959679-b8004eea-4f7e-4fad-b38a-ad1041fbd2f1.png)
![dualuniverse_2023-05-09_01h28m11s](https://user-images.githubusercontent.com/75027025/236959699-f79e04ec-58cd-4bc0-8f4c-3890db1a7299.png)
![dualuniverse_2023-05-09_01h32m22s](https://user-images.githubusercontent.com/75027025/236959710-137b470d-919e-4db2-8d8a-13ba7e95675f.png)  
<br>
<br>
<br>
<br>
   
# HOW TO INSTALL:
**IMPORTANT!**

## Offline:

Unpack the content of the .rar file into DU Dual Universe\Game\data\lua\autoconf\custom folder
Keep DEFAULT++V3 folder and its files as they are in the custom folder


## Online:

Launch the game
ATTENTION: manually link following elements to the control unit (command seat or remote control or ECU)
- Databank
- Fuel Tanks (atmo / space / rocket)
- Radars (atmo and space)
- Manual Switch (will be turned on upon script start, used in the multiple fuel tanks configuration)
- Telemeter (optional)
    

Install the DEFAULT++ vX(rY STABLE WIP) script by right clicking on the control unit, choose Advanced, Run custom configuration
<br>
<br>
<br>
<br>

# USERS MANUAL:

Menus and buttons are operated with the mouse
Windows and widgets can be draged by their tittle bar

| Basic commands | Description |
| ------ | ------ |
| Left Click over button | change the paramater increment (when there is one, increment is shown on the most right like so +-xyz) |
| CTRL + Left Click over a button | to save a button in the Quick Tool Bar (a little asterisk "*" confirms the shortcut is active) |
| Wheel Scroll over button | change the parameter |
| Wheel Scroll over a widget | scale change |
| ALT + 1 | to open and close Main Settings menu |
| ALT + 2 | to open and close Travel Planner++ menu |
| Double ALT + hold | Quick Tool menu and Widgets adjustment menu |

To acces integrated manual user, find the Help Menu button at the bottom of the window Menu Settings

| Chat commands | Description |
| ------ | ------ |
| help | prints the help menu in lua chat tab |
| reset all | formats databank to factory settings |
| ::pos{} | translates map pos to world coordinate |
| align to ::pos{} OR align to vec3() | construct alignment to coordinate |
| align to destination | construct alignment to previous entered coordinates |
| add asteroids ::pos{} | adds asteroids to Travel Planner++ map |
| clear asteroids | clears all saved asteroids |
<br>
<br>
<br>
<br>

# MULTIPLE FUEL TANKS CONFIGURATION:

If total number of elements to be linked and high number of fuel tanks is greater than 10 links!
It is possible to link high number of fuel tanks to 1 or multiple programing boards.

Within the DEFAULT++V3 folder find the "script for FuelTanks on Programming Boards.json" file to be copy pasted in the programing boards

Installation steps are as follow:
- link 1 manual switch to command seat
- Default++ databank needs to be cleared (enter the command reset all in lua chat to clear it)
- link the Default++ databank to each programming board
- link the manual switch to programing board (to a relay then to programing boards if multiple)
- link all the desired fuel tanks to programing boards
- install programing boards script
- turn on the manual switch to initiate the scripts (only once, the first time)
- start the command seat and enjoy (only works with custom widgets, not with default ones)
<br>
<br>
<br>
<br>

# CUSTOM WIDGETS:

Default++ offers a high modularity and unlimited number of custom widgets designed by players
Widgets use Winlib++ operating system from the library files
They can be turned on and off at will from the Main Menu
<br>

To add and load succesfully a new custom widget its name must finish by a number that follows the last one!!!
<br>

| Possible interactions with conf file | Description |
| ------ | ------ |
| Globals | Acces all the conf file globals |
| Flush | Overrides flush, based one Kmph speeds and cruise mode |
| SVG | Displays with or without windows borders any SVG |
| Buttons | Creates interactible buttons |
| Databank | Saves and loads widgets data |
| Keybind | Reads onAction() keybinds |
| Chat commands | Receives text imputs |

<br>
Enough examples are covered in the actual custom widgets files to help you develop a new one
<br>

| Pre-installed Widgets | Description |
| ------ | ------ |
| HUD++ | Alternative flight HUD with integrated gyro |
| Traveler++ | Space travels simple autopilot, interactible with SolarSystem++ |
| SolarSystem++ | Augmented reality solar system and bookmarks display |
| DammageRepport++ | Augmented reality dammage repport |
| DroneFlight++ | Flight mode for drone like constructs using only vertical thrust |
<br>
<br>
<br>
<br>

# UPDATES

| Version | Release note |
| ------ | ------ |
| v3.6 | Released version |
| v3.63 | Added DroneFlight++ widget by Sardini / Increased modularity for custom widgets interaction with the conf file / multi users data saving management / bugs fix | 
<br>
<br>
<br>
<br>

# COPY RIGHTS:

This script is the effort of 6 years development and game mechanics understanding by myself, Jeronimo, is today released open source due to the lack of ambition and features offered by NQ to help us small developers to make DU a better game.

You are free to use / modify it at will, i ll certainly not update it anymore

If anyone is interested to study it and develop further its possibilities, i ll be glad to communicate with you about it and post here some eventual updates made by other players

DISCORD: Jeronimo#4624


