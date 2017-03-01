# blob-slice
Game where player slays malicious blobs with increasing difficulty

Feature Overview:
-
A 2D android and desktop based app in which (from a bird's eye view) the player slices blobs to survive. Blobs are constantly traveling onto the screen, with new and different types appearing every so often. Ideally the player will also be able to buy upgrades with points earned in-game.

MVP:
-
No title screen or upgrades, but a basic verion of gameplay where the player is able to slice blobs as they come onto the screen, increasing the score. No animations for the player or blobs are needed, but there should be at least a few different types of blobs.

Justification:
-
This is a compelling project because I have played a similar game and it ended up being one of my favorite web games. I feel like if I make my version unique enough it may be enjoyable enough to put on the Google Play store. If not, it will still have been a good learning experience and fun to make.

Scenarios:
-
Player clicks mouse in game - attacks with weapon (knife or other)
Player slays the most basic blob - gets some points
Player slays a more advanced blob - gets more points
Player slays multiple blobs at once - gets extra points for a combo
Blob is slayed - bursts and leaves a splatter mark
Time passes - splatter marks gradually disappear over time
User is in "upgrades" tab of menu - able to buy new weapons or other things using points earned in-game
Main menu/title page with functional buttons: play, upgrades, bestiary, instructions, achievements credits and settings
Desktop version: player follows mouse, click to attack
Android version: joystick for movement on bottom left, button to attack on bottom right.
Score counter + settings + pause on top of sides of screen

Goals:
-
I hope to achieve an exciting, fast paced, lagless game experience where the user wants to keep coming back to the game (after buying upgrades or losing). I want the upgrades to be creative and useful, and I would like to have some element of a storyline to the game.
I would also hope to achieve a product of high enough quality that I could upload it to Google Play

Non-Goals:
-
Clone of the game "Amorphous"


Partners and Dependencies:
-
Android Studio SDK https://developer.android.com/studio/index.html
LibGDX https://libgdx.badlogicgames.com/index.html
JBox2D http://www.jbox2d.org/
