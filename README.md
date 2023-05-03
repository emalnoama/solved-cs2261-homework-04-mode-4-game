Download Link: https://assignmentchef.com/product/solved-cs2261-homework-04-mode-4-game
<br>
In this assignment, you will be making a complex game in Mode 4. The complexity expectation is the same as the last assignment, but this time, images are also required. You ​<strong>may not </strong>​extend a game you already made for a previous assignment; ​<strong>you must create something new</strong>​. As a reminder, some suggested games along the complexity level we expect are:

<ul>

 <li>Breakout, with at least 3 rows of 5 blocks (Easy)</li>

 <li>Tetris (Hard)</li>

 <li>Simple flash games (ex. ​http://www.ferryhalim.com/orisinal/</li>

 <li>Simple Neopets games (​http://www.neopets.com/games/​)</li>

 <li>Old Atari games, like Asteroids (​http://www.freeasteroids.org​)</li>

</ul>

Your game must have the following:

<ul>

 <li>At least one struct</li>

 <li>At least one array</li>

 <li>Pooling</li>

 <li>Meaningful text

  <ul>

   <li>It can’t just be present; it needs to be relevant to the game</li>

  </ul></li>

 <li>Non-static text

  <ul>

   <li>This means it changes while you are looking at it (erased then redrawn)</li>

  </ul></li>

</ul>

■   Score that visibly updates during the game is a good example

<ul>

 <li>The following states: Start, Game, Pause, Win/Lose ○ You can have either a Win state, a Lose state, or both.</li>

 <li><strong>DMA used correctly for fillScreen4(), drawRect4(), drawImage4(), and drawFullscreenImage4(). </strong></li>

 <li><strong>At least one fullscreen image </strong></li>

 <li><strong>At least one non-fullscreen image </strong></li>

 <li>At least five moving objects</li>

 <li>At least three buttons used for input</li>

 <li>Collision that matters

  <ul>

   <li>Something must happen whenever two different objects hit each other</li>

  </ul></li>

 <li>A readme.txt file

  <ul>

   <li>An instruction manual (of sorts) that tells a player how to play your game Only a ​<em>minimal </em>​amount of flicker.</li>

  </ul></li>

</ul>




Your code must have the following:

<ul>

 <li><strong>Be entirely written in Mode 4 </strong>

  <ul>

   <li>Having the Mode 3 functions alongside the others in myLib.c is fine, as long as you never call them.</li>

  </ul></li>

 <li>Multiple .c files (more than just main.c and myLib.c)</li>

 <li>At least two .h files</li>

 <li>Good organization (see tips below)</li>

 <li>Meaningful comments</li>

</ul>

<strong> </strong>

<h1>Tips</h1>

<ul>

 <li>Start early. Never underestimate how long it takes to make a game.</li>

 <li><strong>Start over. Do not copy your last game’s code and change it</strong>​, because you will (probably) have to do quite a bit of restructuring to make a Mode 3 game start working in Mode 4.</li>

 <li>Do not draw text every frame. It takes a while to draw, so only update it when it needs to update

  <ul>

   <li>For score, only redraw when the score is different than before.</li>

  </ul></li>

 <li>When splitting code between multiple files, put code that will be useful in multiple games in myLib.c, and code specific to this game in main.c or other files. Those other files should be specific to a concept (collision, etc.).</li>

 <li>Organize your code into functions specific to what that code does. Your main function should not be very long.

  <ul>

   <li>Having ​update() and ​​draw() functions that you call in ​ ​main() is helpful.​</li>

  </ul></li>

</ul>

○    Make sure the order takes into account waiting for vblank at the correct times to minimize flicker.

<ul>

 <li>Build upon the myLib.c and myLib.h files from previous assignments (especially Lab05).</li>

</ul>