---
layout: project
type: project
image: images/M.game .png
title: Miensfeld
permalink: projects/Miensfeld
# All dates must be YYYY-MM-DD format!
date: 2015-01-12
labels:
  - C
  - GitHub
summary: A simple Miensfeld game develop during EE160.
---
To move about in the minefield, you use the keyboard. You can move Timmy in any of the 8 directions from his current position by using the 8 keys surrounding the 'j' key:
<img class="ui image" src="{{ site.baseurl }}/images/move_around.png">
As Timmy moves through the field, he indicates safe cells (cells known to not contain a mine) on his map.

Detecting Mines
To help Timmy find his way through the mines, he is equipped with a "proximity probe" which tells him how many mines there are in the 8 cells surrounding him (today's modern Army has all the coolest gadgets). Unfortunately, the probe cannot tell him where those mines are, just how many.

Planting Flags
However, Timmy is also equipped with a limited number of hi-tech indicating flags to use to indicate cells to avoid by others behind him. He may plant a flag (using the keyboard) in any of the 8 surrounding cells when he suspects there is mine there. The keys to plant a flag are the shifted versions of the movement keys: 
<img class="ui image" src="{{ site.baseurl }}/images/planting_flags.png">
When planted, the flag will indicate whether there is a mine there or not.

Earning Points
Timmy earns 1 point for each new safe cell he finds by moving into it. In addition, he earns 2 points for each flag he plants correctly in a cell that contains a mine. However, he loses 1 point for each flag he plants in a cell that does not contain a mine.
If Timmy successfully makes it to the other side of the minefield, he earns a bonus of 10 points.

The game ends when Timmy either reaches the other side of the field :-), or gets blown up by stepping on a mine :-(.

For this project, we worked in group of 3 and I was working mainly on the planting flag part while my teammate worked on the other area. Once we complete all the parts, we merge the codes together and debug. 
</div>
