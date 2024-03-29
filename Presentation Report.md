<section class="Tetris!">
 <h2>Tetris!</h2>
</section>

<p><a href="https://hci-game-interface.github.io/P2.7/">Play Game</a></p>

What is Tetris and how to play this?

Tetris is a tile-matching puzzle video game. It is primarily composed of a field of play in which pieces of different geometric forms, called "tetriminos", descend from the top of the field.During this descent, the player can move the pieces laterally and rotate them until they touch the bottom of the field or land on a piece that had been placed before it. 

The objective of the game is to use the pieces to create as many horizontal lines of blocks as possible. When a line is completed, it disappears, and the blocks placed above fall one rank. Completing lines grants points, and accumulating a certain number of points moves the player up a level, which increases the number of points granted per completed line.

The game interface looks like this

<img src="https://user-images.githubusercontent.com/58001098/70399482-ffecba00-19e9-11ea-90bd-c3df9d18b8c5.gif" width="700">

| Team Members      | Duties                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Vineela Aradhyula <br><img src="https://user-images.githubusercontent.com/58001098/69386331-f80de580-0c87-11ea-9ef6-67ca9ca6e530.jpg" width="100"> | Set up Tetris game board<br>Created various Tetris shapes<br>Implemented keyboard movement<br>Created levels for the game<br>Display Current Score, High Score and Lines<br>Presentation Report creation<br>Makes sure that ‘Golden Rules & Principles’ are followed |
| Nitisha Patange  <br><img src="https://user-images.githubusercontent.com/58001098/69386759-1fb17d80-0c89-11ea-851f-673eed82470f.jpeg" width="100">  | Implemented ‘Pause’ feature so that the player can pause the game <br>and resume it to continue without loosing the score<br>Set up the timer to track the game time                                                                                                                                                                                                                                                                                             |
| Sonali Singh  <br><img src="https://user-images.githubusercontent.com/58001098/69386855-6ef7ae00-0c89-11ea-87a4-2224ca63051f.jpeg" width="100">    | Added the background design and image for the interface<br>Implemented music feature, where the game exhibits different <br>sounds while playing                                                                                                                                                                                                                                                                                                                    |    
<section class="Sketches">
      <h3>Sketches</h3>
      </section>                                                       

These are our sketches

<img src="https://user-images.githubusercontent.com/58001098/69388267-e7606e00-0c8d-11ea-9153-b450e0bb1ca0.png" width="400"> <img src="https://user-images.githubusercontent.com/58001098/69388390-5342d680-0c8e-11ea-9fc9-6648081993dd.png" width="400">
<img src="https://user-images.githubusercontent.com/58001098/69388470-8be2b000-0c8e-11ea-9db6-d11fa8104dd9.png" width="400">

<section class="Our Work/ Main Functions">
      <h3>Our Work/ Main Functions</h3>
      </section>     
<br>1. Game board : An elegant Tetris game board with various Tetris shapes is implemented
<br>2. Keyboard movement : Controls are created to move the blocks

| Control      | Symbols                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Move Left            | ← |
| Move Right           | → |                                                                                                   
| Drop                 | ↓ | 
| Rotate Clockwise     | ↑ | 
 
<br>3. Lines : Whenever all the cells of a row (also called line) of the game board are occupied, the line is cleared; all blocks above it are lowered by one row (and no more). This row clearing can happen for several lines simultaneously.
<br>4. Score & High Score : When the player forms a line, the score keeps adding up and the raise depends on how well the player is constructing the blocks. High Score is the highest score achieved by the player in the game.
<br>5. Level : Based on the score achieved, the player will move to the next level. Score required to move to the 2nd level is 100.
<br>The design looks like this with the 'scores' and 'Level' implementation without Timer, Music and Pause/Resume.
<img src="https://user-images.githubusercontent.com/58001098/70393772-77ebbd80-19b3-11ea-9674-316e379c7969.png" width="400">
<br>6. Pause/Resume : A pause and resume function through which you can pause the game whenever you want and resume it without losing the score. 
<br>7. Timer : There is also a time tracker function for Tetris which will show for how much time you have played the game.
<br>8. Music : By implementing the looping code for the background music. When the program runs and the music plays and after certain time there is change in the music as you move forward with the levels.
<br>9. UI Implementation : Embedded and collaborated the code to check if all the features are working properly and also set up a background image for the game.
<br>After adding all the features the design looks like this.
<br>
<br><img src="https://user-images.githubusercontent.com/58001098/70399203-88b62680-19e7-11ea-9c51-178b576cabd7.png" width="400">
<br>10. The interface is visually appealing with a background image
<br>11. The interface is created by following the ‘Golden Rules & Principles’ such as consistency, color, background, font, size etc that is covered in the class

<section class="References">
      <h3>References</h3>
      </section>

https://www.youtube.com/watch?v=Wcb0_Q9r6i4
<br>https://www.youtube.com/watch?v=d8Cn_H51PmI
