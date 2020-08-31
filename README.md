# Quadris
Single player tetris game made in C++

Supports 5 levels of difficulty varying random block generation probabilities along with extra obstacles

Includes a tetris AI that can automatically play the game and provide hints to the player.
Based on a genetic algorithm that weighs 4 different heuristics
(Height, Completed Lines, Holes, and Bumpiness).

# Libraries
Graphics display created using X11Lib

# Compile
Ensure that X11Lib is installed

If on windows, Xming in conjunction with WSL is an alternative. 
Simply install [Xming](http://www.straightrunning.com/XmingNotes/) and [Xming-fonts](http://www.straightrunning.com/XmingNotes/)

Nagivate to the src directory, type "make" in your terminal to compile the program.
Then "./quadris" to run the game.
