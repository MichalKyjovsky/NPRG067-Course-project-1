# NPRG067-Course-project-1
Following repository suppose to store the first of two mandatory semestral projects from subject NPRG067 - Python for practice, necessary to obrain the course credit.

## Assignment description
The goal is to create a turn-based artillery game (see, e.g., the Scorched Earthgame).  The  game  screen  consists  of  a  terrain,  on  which  the  players  areshown (as a small tank or cannon). The players in turns try to shoot each other(the winner is the last remaining player). The shooting is controlled by specify-ing the angle (from -180 till 180 degrees) and power of the shot (0 – 100). Theprojectile trajectory is influenced by the gravity (i.e., the shot curve is parabol-ic).  The  window  edges  are  “rubber”,  i.e.,  the  projectiles  bounce.  The  projec-tiles  “draw”  their  flight  trajectory  (to  allow  the  player  to  more  accurately  ad-just the shot on their next turn).

### Platform specification

- Use either Tkinter or Kivy for graphics.
- Multiplatform

### Required features

- The shape of the terrain is randomly generated and resembles “mountains”.
- The complete game is visible in the window, i.e., the terrain does not scroll to left/right. Choose a suitable win-dow size.
- The  number  of  the  players  is  configurable  at  the  start  of  the  game  (via  a  text  box  or  combo-box  or  similar).
- There are only “human” players (i.e., no AI players).The game manages a “hall of fame” list, where, at the end of the game, the winner can put his name. 
- The size ofthe list is 10 last winners.

### Optional features

- There  is  wind  (blowing  at  a  random  strength  from  right  or  left)  that  influences  the  projectiles,  i.e.,  the  shotcurve is ballistic.
- The shot impacts influence the terrain, i.e., part of the terrain is removed.
- The terrain is larger than the game window, i.e., the terrain can be scrolled to left/right.
- There are also AI players.

#### Additional resources

1. https://en.wikipedia.org/wiki/Scorched_Earth_(video_game)
2. https://archive.org/details/msdos_Scorched_Earth_1991
