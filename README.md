# The Cat Trap
An intelligent that plays the Cat Trap game using the Minimax algorithm, with Alpha-Beta pruning and Iterative Deepening. This is the project showcased in the LinkedIn Learning course titled AI Algorithms for Gaming.

# Playing the Game in your own Python setting
You'll need Python 3, numpy and PyQT5. Simply run the command `python CatTrap.py`

### Play it online! ###
You may also play with the code (and the cat) at Repl.it: https://repl.it/@kuashio/cat-trap-game

# Controls

- **Button - Start New Game Button:** Starts a new game on an NxN hexgrid with a random number of blocked tiles (between 6.7% and 13%).
- **Text - Hexgrid Dimensions (N):** The number of rows and columns in the next hexgrid that will be created by the button above.
- **Text - Deadline:** Deadline for Iterative Deepening to comply, or Timeout for all other techniques. If a timeout is reached, the cat is removed and loses after the next player's move.
- **Checkbox - Random Cat:** Use a random cat.
- **Checkbox - Alpha-Beta Pruning:** Add Alpha-Beta Pruning to the cat.
- **Checkbox - Limited Depth:** Use Depth-Limited Search.
	- **Text - Depth:** The maximum depth to explore with Depth-Limited Search.
- **Checkbox - Iterative Deepening:** Use Iterative Deepening with the deadline entered above.
- **Checkbox - Edit Mode:** Toggle Edit mode. In this mode, tiles are toggled by clicking on them. To move the cat, first click on the cat, then click on the new desired location of the cat.


# Source Files
- **CatTrap.py** - The GUI and main function are in this file. Run this file to play the game.
- **CatGame.py** - The algorithms are implemented in this file. This is the  source code exposed in the LinkedIn Learning course.
- **hexutil.py** - A library that enables printing the hexgrid on the screen.

# Contact
Eduardo Corpeño

kuashio@gmail.com

Enjoy!
