# Godot NX Ports (Repository is currently a WIP)
A compilation of open-source Godot homebrew ports for the Nintendo Switch using Stary2001's Godot engine port. Some ports may have bugs that will be listed in each individual game section. Some games may have a small amount of microstutter and longer-than-normal load times, but not to the point of being unplayable. 

## [Hunt for the Shadow Rider](https://github.com/faithvoid/GodotNXPorts/releases/tag/HuntForTheShadowRider) 
### by [bluestreak0](https://bluestreak0.itch.io/) 

![A rogue Shadow Rider has escaped to the year 2078. You are the only Hunter left who can take him down.](https://img.itch.zone/aW1hZ2UvNDkxMDQ0LzI1MzgyODEucG5n/original/65Q4iQ.png)
*<p align="center">A rogue Shadow Rider has escaped to the year 2078. You are the only Hunter left who can take him down.</p>*

Controls:
- D-Pad or Analog: Move (L+R) / Jump + Climb (Up) / Crouch (Down)
- B: Jump/Up (to make jumping a bit easier) / Cancel
- Y: Shoot
- Plus: Pause
- Minus: Quit

Bugs:
- Currently this can only really be played in handheld mode (with a working touchscreen) due to the menu requiring a mouse click, which is emulated via the touch screen. Hopefully I can set the right analog stick + right trigger to work as a mouse + left click in the next update, but I'm still learning the ins and outs of Godot scripting.
- There may be some slowdown whenever new assets load in, but it's usually for a blip of a second and the game is short enough where it's not particularly a hindrance. The Switch has a tendency to not like loading multiple files at the same time that seems to lead to microstutters in a good chunk of Godot titles, so I'm not really sure how to work around it. I've tried tweaking a whole series of performance settings to no avail, so suggestions are appreciated!
- Analog support isn't working due to the fact that combining it with the B-button jump leads to the character very slowly running to the edge of the screen until you spam the controls non-stop. Not sure what that's about, but it's a platformer so you should use a decent d-pad anyway. ;P


## [Titan Tactics](https://github.com/faithvoid/GodotNXPorts/releases/tag/TitanTactics)
### by [Team Potato](https://team-potato.itch.io/) 
*<p align="center">![A follow up to Pocket Tactics, Titan Tactics is inspired by the awesome tactic games of the 90s. Fight with your allies and uncover the mysteries of the kingdoms of Tyrmyr and Skathi!](https://img.itch.zone/aW1hZ2UvODA1NTYxLzU2NDM3MjUucG5n/original/xuUZnE.png)</p>*
*<p align="center">A follow up to Pocket Tactics, Titan Tactics is inspired by the awesome tactic games of the 90s. Fight with your allies and uncover the mysteries of the kingdoms of Tyrmyr and Skathi!</p>*


Controls (based off of the Dualshock controller prompts):
- D-Pad: Move Cursor
- B: Accept
- A: Cancel
- X: Menu / End Turn
- Y: Swap Character
- L/R: Rotate camera
- Plus: Pause

Bugs:
- Load times take a few seconds + the framerate absolutely tanks for 3-4 seconds when the battle movement squares show up. Something about either Godot or this game hammers one of the CPU cores and causes this. Since it's a turn-based RPG it doesn't affect gameplay a TON, but it's still a bit annoying regardless.

## [Pocket Tactics](https://github.com/faithvoid/GodotNXPorts/releases/tag/PocketTactics)
### by [Team Potato](https://team-potato.itch.io/) 
*<p align="center">![Strategy RPG Gameboy demake in 4 shades of green!](https://img.itch.zone/aW1hZ2UvNzQ5ODQzLzQxOTgyMDAucG5n/original/RkrhPA.png)</p>*
*<p align="center">Strategy RPG Gameboy demake in 4 shades of green!</p>*

Controls:
- D-Pad: Move Cursor
- A: Accept
- B: Cancel

## [Untold](https://github.com/faithvoid/GodotNXPorts/releases/tag/PocketTactics)
### by [JohnGabrielUK](https://JohnGabrielUK.itch.io/) 
*<p align="center">![In the aftermath of destiny, at the precipice of fate,
a tale that was never meant to be told awaits its chance to be heard.](https://img.itch.zone/aW1hZ2UvNzQ5ODQzLzQxOTgyMDAucG5n/original/RkrhPA.png)</p>*
*<p align="center">In the aftermath of destiny, at the precipice of fate,
a tale that was never meant to be told awaits its chance to be heard.</p>*

Controls:
- D-Pad: Move / Turn
- Start: +
- Map: X
- Bomb: Y
- Use: A
