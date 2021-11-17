# volumeincrement
This project is to change Windows' volume step


You'll need AutoHotkey to get the program to work.

To be able to change the increment/decrement step, you'll need to modify line 5 (volume increment) and line 11 (volume decrement):
SoundSet, volume + 5
SoundSet, volume - 5

Change the "+ 5" and "- 5" to whatever value you want.

In order to have the script to start when your computer boots up, place the file "volume.ahk" in "shell:startup"



Source: https://www.addictivetips.com/windows-tips/change-volume-increment-levels-on-windows-10/
