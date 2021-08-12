# This is a Minecraft 1.12.2 ComputerCraft program to predict moon phases and constellations for Astral Sorcery and Thaumcraft 6.  Part of the constellation prediction is tracking the solar eclipses.
This program should support later versions of Minecraft and Astral Sorcery.  I am not sure the constellation data will be correct for those versions.

In order to use this program you will need an advanced computer and 9 advanced monitors from ComputerCraft. Download the **startup** file and the 8 ComputerCraft **img** files from this git and transfer them all to your computer inside the game.

In the game stack the monitors into the 3x3 wall.  Place the computer touching one of the monitors (any side except the monitor front should work).
Then you will need to know the day when an eclipse occurs.  Easiest way to get it is typing in the following on the monitor the day you see an eclipse.
```
lua
os.day()
exit()
```
Then edit the **startup** file and change the number for the eclipse constatnt.  The example in the program has it set to day 17.  But it can be any day the eclipse occurs.
```
eclipseConstant = 17
```
Save the program and reboot the computer or run **startup** and it should display the constelations along the left, and image of the moon to the right and below the moon should be the name for the current moon phase and the number of minecraft days to the next eclipse.
