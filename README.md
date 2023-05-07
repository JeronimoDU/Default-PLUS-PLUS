# Default-PLUS-PLUS
Dual Univers Advanced flight script

Default++ developed since 2017, is the most advanced and innovative flight script with a unique navigation operating system Winlib++.
DU flight parameters are brought to you to an other level with dozens and dozens of customizable settings.



HOW TO INSTALL:
---------------

-Offline:

Unpack the content of the .rar file into DU Dual Universe\Game\data\lua\autoconf\custom folder
Keep DEFAULT++V3 folder and its files as they are in the custom folder


-Online:

Launch the game

ATTENTION: manually link following elements to the control unit (command seat or remote control or ECU)

    Databank
    
    Fuel Tanks (atmo / space / rocket)
    
    Radars (atmo and space)
    
    Manual Switch (will be turned on upon script start)
    

Install the DEFAULT++ vX(rY STABLE WIP) script by right clicking on the control unit, choose Advanced, Run custom configuration


USERS MANUAL:
-------------

Menus and buttons are operated with the mouse
Windows and widgets can be draged by their tittle bar

Left Click over button = change the paramater increment (when there is one, increment is shown on the most right like so +-xyz)
CTRL + Left Click over a button to save a button in the Quick Tool Bar (a little asterisk "*" confirms the shortcut is active)
Wheel Scroll over button = change the parameter
Wheel Scroll over a widget = scale change

ALT + 1 = to open and close Main Settings menu
ALT + 2 = to open and close Travel Planner++ menu
Double ALT + hold = Quick Tool menu and Widgets adjustment menu

To acces integrated manual user, find the Help Menu button at the bottom of the window Menu Settings

chat commands:
help = prints the help menu in lua chat tab
reset all = formats databank to factory settings
::pos{} = translates map pos to world coordinate
align to ::pos{} OR align to vec3() = construct alignment to coordinate
align to destination = construct alignment to previous entered coordinates
add asteroids ::pos{} = adds asteroids to Travel Planner++ map
clear asteroids = clears all saved asteroids


MULTIPLE FUEL TANKS CONFIGURATION:
----------------------------------

If total number of elements to be linked and high number of fuel tanks is above 10 links
It is possible to link high number of fuel tanks to 1 or multiple programing boards

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





