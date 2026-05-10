# Java-Snake-Game
Java Snake game source code
Snake
Snake is an older classic video game. It was first created in late 70s. Later it was brought to PCs. In this game the player controls a snake. The objective is to eat as many apples as possible. Each time the snake eats an apple its body grows. The snake must avoid the walls and its own body. This game is sometimes called Nibbles.

Development of Java Sname game
The size of each of the joints of a snake is 10 px. The snake is controlled with the cursor keys. Initially, the snake has three joints. If the game is finished, the "Game Over" message is displayed in the middle of the board.

First we will define the constants used in our game.
private final int B_WIDTH = 300;
private final int B_HEIGHT = 300;
private final int DOT_SIZE = 10;
private final int ALL_DOTS = 900;
private final int RAND_POS = 29;
private final int DELAY = 140;
The B_WIDTH and B_HEIGHT constants determine the size of the board. The DOT_SIZE is the size of the apple and the dot of the snake. The ALL_DOTS constant defines the maximum number of possible dots on the board (900 = (300*300)/(10*10)). The RAND_POS constant is used to calculate a random position for an apple. The DELAY constant determines the speed of the game.

private final int x[] = new int[ALL_DOTS];
private final int y[] = new int[ALL_DOTS];
These two arrays store the x and y coordinates of all joints of a snake.


Figure: Snake
This was the Snake game in Java.
