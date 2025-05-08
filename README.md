# Advanced 2 way movement with gravity in GML2 code for 2D games
For this GML2 project I named the player sprites and object as "spr_player", "spr_player_walk", "spr_walk_left" and "obj_player";
<br>
<br>
The sprite and object for the ground are "spr_gnd" and "obj_gnd";
<br>
<br>
You may name these however you please.
<br>
<br>
I used the arrow keys only as an example of input for movement and jumping, but if you wish to use other keys like A and D for movement and space for jumping you can write the binds like this:
```
var _right = keyboard_check(ord("A"));
var _left = keyboard_check(ord("D"));
var _up = keyboard_check(vk_space);
```
