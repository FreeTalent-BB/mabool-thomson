# Mabool for Thomson Computers(MO5 & TO7/70)

Map files used by the Map editor "TILED" that you can find here : https://www.mapeditor.org/

<b>map.tmx</b><br>
The file of the all Mabool stages.

<b>title.tmx</b><br>
Not used. Just a map for the title screen of Mabool.

<b>HOW TO EDIT MY STAGES?</b><br>
Do a backup of the <b>map.tmx</b> file. Open the map.tmx file in the TILED editor. You will find the original 16 stages of Mabool. Each stage is placed in a layer, keep this organization. 

<b>Rules for creation</b>
- 1 Mabool (mandatory)
- 1 door (mandatory)
- 0 or many walls
- 0 or many broken grounds
- 0 or many stars
- 0 or many keys
- 0 or many elevators
- 0 or many boxes
  - NOTE: The direction of the elevator is determined by the single empty space that will be near it.
- 0 or 2 teleporters
- 0 or 1 laser switch (always ON by default)
- 0 or 20 lasers max

<b>HOW TO MODIFY THE NUMBER OF STAGES?</b><br>
By default, Mabool has 16 stages. If you want to create a different number of stage, you must modify the file "VARS.rscript" in the "inc" folder by changing the line:
```
#const c_max_levels=16
```
with your number of levels.

