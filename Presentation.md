<section class="Tetris!">
 <h2>Tetris!</h2>
</section>

<p><a href="https://hci-game-interface.github.io/Project-2---Tetris/">Play Game</a></p>

What is Tetris and how to play this?

Tetris is a tile-matching puzzle video game. It is primarily composed of a field of play in which pieces of different geometric forms, called "tetriminos", descend from the top of the field.During this descent, the player can move the pieces laterally and rotate them until they touch the bottom of the field or land on a piece that had been placed before it. 

The objective of the game is to use the pieces to create as many horizontal lines of blocks as possible. When a line is completed, it disappears, and the blocks placed above fall one rank. Completing lines grants points, and accumulating a certain number of points moves the player up a level, which increases the number of points granted per completed line.

<img src="https://user-images.githubusercontent.com/58001098/70393481-f7778d80-19af-11ea-88a0-5279215c2990.gif" width="1000" height="500">



| Team Members      | Duties                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Vineela Aradhyula <br><img src="https://user-images.githubusercontent.com/58001098/69386331-f80de580-0c87-11ea-9ef6-67ca9ca6e530.jpg" width="100"> | Set up Tetris game board<br>Created various Tetris shapes<br>Implemented keyboard movement<br>Created levels for the game<br>Display Current Score, High Score and Lines<br>Presentation Report creation<br>Makes sure that ‘Golden Rules & Principles’ are followed |
| Nitisha Patange  <br><img src="https://user-images.githubusercontent.com/58001098/69386759-1fb17d80-0c89-11ea-851f-673eed82470f.jpeg" width="100">  | Implemented ‘Pause’ feature so that the player can pause the game <br>and resume it to continue without loosing the score<br>Set up the timer to track the game time                                                                                                                                                                                                                                                                                             |
| Sonali Singh  <br><img src="https://user-images.githubusercontent.com/58001098/69386855-6ef7ae00-0c89-11ea-87a4-2224ca63051f.jpeg" width="100">    | Added the background design and image for the interface<br>Implemented music feature, where the game exhibits different <br>sounds while playing                                                                                                                                                                                                                                                                                                                    |                                                                    |

Sketch UI :

<img src="https://user-images.githubusercontent.com/58001098/69388267-e7606e00-0c8d-11ea-9153-b450e0bb1ca0.png" width="400"> <img src="https://user-images.githubusercontent.com/58001098/69388390-5342d680-0c8e-11ea-9fc9-6648081993dd.png" width="400">
<img src="https://user-images.githubusercontent.com/58001098/69388470-8be2b000-0c8e-11ea-9db6-d11fa8104dd9.png" width="400">

<br><br>Main functions :
<br>
<br>1. An elegant  Tetris game board with various Tetris shapes will be implemented
<br>2. Keyboard movement will be created to move the blocks
<br>3. ‘Levels’ feature will be created for the player to move to the next level
<br>4. Current Score and High Score information will be shown up on the interface
<br>5. A timer will be set to track the game time
<br>6. ‘Pause’ and ‘Resume’ options will be provided for the player to stop the game in between and continue from there
<br>7. The interface will have visually appealing design and background image
<br>8. Music feature will be implemented to produce different sounds when the game is being played
<br>9. The interface will follow all the ‘Golden Rules & Principles’ such as consistency, color, background, font, size etc that is covered in the class


How far did you go with the implementation?

We did set up the game board and a background image and will add other features soon

The plan to move forward?

We will move with the implementation as shown in the sketches above.
<br>Step 1 - Game Board, Blocks, Timer
<br>Step 2 - Next block, Current Score, High Score
<br>Step 3 - Pause/Resume game, show up levels



<section class="Task Description">
      <h2>Task Description</h2>
       <p>
        Hi there, just play! (Controls listed below)
      </p>
       </section>
   </header>
  
  Use the controls with the help of a keyboard and play the game. When all the cells of a row of the game board are occupied we say that the line is cleared and the score comes up and the player sees the raise in the 'lines' as well. When the player achieves the score of 100, the player moves to the next level and this keeps going. The high score will be shown to the player to check the highest score made in the game.
  
<section class="controls">
      <h3>Controls</h3>
      <ul>
        <li>Left/right arrow keys: move left/right</li>
        <li>Up arrow : rotate clockwise</li>
        <li>Down arrow:  drop faster (move down faster)</li>
      </ul>
    </section>

<section class="Hypothesis">
      <h2>Hypothesis</h2>
      </section>

The game of Tetris is played on a rectangular board consisting of square (initially empty) cells. The board is of fixed and seven game pieces can be used, each covering board cells usually called blocks. These pieces are known as (from left to right) --> O or square, 
--> J or leftgun,
--> L or rightgun, 
--> I or dash, 
--> Z or leftsnake, 
--> S or rightsnake, and T or tee:

This interface generates a sequence of pieces that drop down from the top of the board until they rest on top of  previously dropped pieces or on the bottom of the game board. The user/player can determine the position and orientation of the pieces
by rotating and moving them horizontally while they fall. 

Lines : Whenever all the cells of a row (also called line) of the game board are occupied, the line is cleared; all blocks above it are lowered by one row (and no more). This row clearing can happen for several lines simultaneously.

Control :

| Control      | Symbols                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Move Left            | ← |
| Move Right           | → |                                                                                                   
| Drop                 | ↓ | 
| Rotate Clockwise     | ↑ | 


Level : Based on the score achieved, the player will move to the next level. Score required to move to the 2nd level is 100.

Score & High Score : When the player forms a line, the score keeps adding up and the raise depends on how well the player is constructing the blocks. High Score is the highest score achieved by the player in the game.

Background Music : There is a music set in the game background and this starts when the player runs the code for game.
