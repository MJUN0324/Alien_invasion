
In Alien invasion, the player controls a rocket ship that appears at the bottom center of the screen. 
The player can move the ship right and left using the arrow keys and shoot bullets using the spacebar.
    When the game begins, a fleet of aliens fills the sky and moves across and down the screen. 
    The player shoots and destroys the aliens. 
        If the player shoots all the aliens, a new fleet appears that moves faster than the previous fleet. 
    If any aliens hits the player's ship or reaches the bottom of the scren, the player loses a ship.
    If the player loses three ships, the game ends.

draft 
examine our code and determine if we need to refactor before implementing new features
add a single alien to the top-left corner of the screen with appropraite spacing aroundit.
use the spacing around the first alien and the overall screen size to determine how many fliens can fit on the screen. We'll write a loop to create aliens to fill the upper portion of the screen.
make the fleet move sideways and down until the entire fleet is shot down, an alien hits the ship, or an alien reaches the ground. If the entire fleet is shoot down, we'll create a new fleet. If an alien hits the ship or the ground, we'll destroy the ship and create a new fleet.
Limit the number of ships the player can use, and end the game when the player has used up the allowed number of ships
