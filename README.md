# Sausage Savior

A skeleton of a game i created as part of a game jam. The game jame concept was to create any game involving food. The project uses Unity, most of the code outside of boilerplate and all of the art was created by me. I use Aseprite to create art and animations. While i never completed the game, most of the core mechanics are in place. 

Check it out at the github.io deployment, hope you have fun!: 

https://blueishtsunami.github.io/SausageSavior/

NOTE: This game was being designed for use by mobile users, but should work on pc too. 
- For mobile, use the joystick in the bottom left to move, and tap the screen to jump
- For desktop, use the arrow keys to move, and spacebar to jump. 

Mechanics: 
- You are a sausage
- You have to maintain your temperature
- There are pickups that boost you (Mustard, ketchup, bun)
- (Not Completed) Your ending score for a level will depend on temperature, and how many pickups you have. A perfect score is cooked just right with all of the fixings. 

Areas of note: 
- Created a customized character controller for movement. The default boilerplate controllers in unity are not the best, so I needed to create a controller that would allow for better platforming controls. Things to keep in mind are precision, momentum, and general feel for the player.
-  I created all of the graphics in the game by hand. While they may not look impressive, this is a painstaking effort. Each feature to be added required all new artwork.
-  Getting the pickups to sync with the character visually was tough at first. the animations did not want to sync, and they would overlap incorrectly. 
-  Creating the parallax code for the background elements to move at different rates and repeat was surprisingly annoying to get right.
-  Spent a lot of time on the camera controller to get smooth movement to follow the character. More to be done there. 
-  Midway through the project, Unity had some major updates that messed with my project. Hopefully I'll pick it up again oneday. 

