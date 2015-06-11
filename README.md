Tetris
======

A tetris game in C using NCURSES.  It's pretty feature complete, except for
stretch goals I may pick up in my free time.


Instructions
------------

To build, all you need to do is run `make`.  Then run `bin/release/main` to play
the game.

The controls are typical of Tetris - left and right to move the tetromino, up
rotates (clockwise?), and down immediately drops the tetromino (not a fast drop,
an immediate drop).  The `q` key will exit the game prematurely.


Future/Stretch Goals
--------------------

* Pause button.
* Store a block.
* Save/load games.
* MIDI Tetris theme song playback.
* Networked multiplayer!
