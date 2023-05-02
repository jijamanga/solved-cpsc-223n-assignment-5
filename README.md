Download Link: https://assignmentchef.com/product/solved-cpsc-223n-assignment-5
<br>
<strong> </strong>

<strong>Falling Apples</strong>

<strong>Introduction</strong>

Think about an apple tree where the apples are ripe for harvesting.  If the apples are not picked when ripe they begin to fall to the ground.  If an apple falls and hits the ground it is damaged for retail sale.  There is a eight year old boy under the tree with a baseball mitt whose job is to catch each apple before it hits the ground.

<strong>Description of the basic falling apples game</strong>




The red circles represent red apples falling from a tree.  The tree is tall and is outside the view of the interface.  Each apple has a radius equal to 8 pixels.  The apples fall from the tree directly downward to the ground.




The apple tree is in an orchard.  The ground is brown dirt.  The sky is light blue.  In the distant horizon the sky meets the ground.   Apples fall from the tree (not seen) at random times.  Your job is to catch the apple by clicking the mouse on the red falling apple.  If the apple has reached the yellow control panel then it is too late – the apple is damaged.  If the apple is in the blue sky area it is too high – you can’t reach it.  The only time you can catch the apple is when it is low enough.  To catch the apple it must reach or pass the horizon line.




You “catch” an apple by clicking the cursor on the red ball.  That is considered a catch.  When an apple has been caught it disappears from view, and of course, the apple caught counter increases by one.




Apples fall from the tree at random places.  Lets suppose the width of your user interface is 1280 pixels.  Then your program picks a random place between 8 and 1272 for the starting place of the apple.  [Don’t pick a place close to the edge because the apple may be partially hidden from view.]




You decide the linear speed of the falling apples.  Pick a nice moderate speed: not too slow and not too fast.




After a certain number of fallen apples the game stops.  For example, after say 10 apples the game is over.   You decide how many apples to allow.




<strong>The advanced game</strong>

<strong> </strong>

You are invited to enhance the basic game.  Here are the ideas.




The apples do not fall one by one.  Sometimes the second apple will begin to fall before the first apple is caught or hits the ground.  Enhance your game by allowing two concurrently falling apples.




As the game progresses the wind speed increases.   Therefore, successive apples begin to fall faster than the previous apples.  Enhance your game by making each additional apple fall slightly faster than its predecessor.




You pick an advanced option and implement it.






























































