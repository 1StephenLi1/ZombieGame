# Zombie Apocalypse v4.4 

## Description

At the beginning of the program a single zombie awakes and begins to move around the grid. It is given an initial x-y coordinate and a list of movements, up, down, left and right (U,D,L,R).

The ordered sequence of movements is represented as a string, for example: DLUURR (down, left, up, up, right, right). Zombies can move through the edge of the grid, appearing on the directly opposite side. For a 10x10 grid, a zombie moving left for (0,4) will move to (9,4); a zombie moving down from (3,9) will move to (3,0). The poor creatures in the area are the zombie’s victims. The also have an initial x-y coordinate. The creatures are aware of zombie presence, but are so frightened that they
never move.

If a zombie moves so that it end up on the same location as a creature, the creature is transformed into another zombie and zombies score one point. The zombie continues moving and infecting creatures until has performed all its moves. Once it has completed its movement, the first newly created zombie moves using the same sequence as the original zombie. Once it has completed its move, the second newly created zombie moves, and so in order of infection with each zombie performing the same sequence of moves. Once no new zombies have been created and all the zombies have completed moving the program ends.

## How to run it

Please open the file zombie_apocalypse.html in a browser. Then upload a text file by clicking 'Choose file' option. Once uploaded, the output will get displayed on the screen.

(Please note the uploaded text file must have the same format as the given example)

## Authors

* **Stephen Li**
