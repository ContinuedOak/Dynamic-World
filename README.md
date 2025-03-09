# Dynamic World Tech Demo

This project is used to demonstrate the technology behind Unity HDRP Volumetric Clouds and Day/Night Cycle

This project is not to be distributed outside of this GitHub project repository, the following project is used for tech demonstration ONLY and if to be shared must be shared via the GitHub link only.

# List of Weather Types
- Clear
- Cloudy
- PartlyOvercast
- Overcast
- Foggy
- Drizzling
- Rain (no rain particles yet)
- Thunderstorm (no rain or lightning particles yet)
- Snow

# Commands Guide
in order to use command, press F4 on the keyboard
you must also use '/' before any command (ie; /weather clear)

# List of Commands

## World

- /timescale <number> (Changes the world either by speeding it up or slowing it down, default = 1f)
- /weather <string or number> (forcefully sets the current weather to whatever you want)
- /getweather (allows you to see all the weather possibilities)
- /localtime (toggles the in-game time to be the time set on you local device, aka real world time)
- /freezetime (toggles whether the current in-game time is frozen or moving)

## Player

- /setplayerspeed <number> (changes the player walking speed, default = 2f)
- /setplayersprintspeed <number> (changes the player sprinting speed, default = 5.335f)
- /setplayerjumpheight <number> (changes the player jumping height, default = 1.2f)

## Game

- /fullscreen (toggles fullscreen)

## Visual Management

- /createprimitive <string> (create a primitive gameObject at 0,0,0)
- /createprimitivelist (shows you a list of what primitive you can create

## Base Commands

- /savelogtofile (saves the current log to a text file used to read at a later date)
- /clear (clears the log)
- /quite or /q (forcefully closes the game)
- /help (shows a list of all commands)

## Scene Management

- /sceneload <string> (will forcefully load a scene)
- /sceneunload <string> (will forcefully unload a scene)
- /scenelist (will display a list of all possible scene that are attached and can be loaded)
