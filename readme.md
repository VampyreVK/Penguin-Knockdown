# Final Project Proposal: XR Arcade

*Penguin Knockdown*

*Viviana Jenkins*

## Project Description

Penguin Knockdown is an augmented reality recreation of the classic Knock-Em-Down carnival game that is sure to have you throwing your controller against the wall in fits of rage when the dang penguins just WON'T GO DOWN!!!!! Trauma aside, this project aims to utilize spatial data to place the penguin game relative to your real life space, and allows you to shoot the balls using a controller to knock down penguins and maybe even win a prize if you are lucky!

## Feature Breakdown

1. **Knocking Down Penguins**: Allows the player to shoot balls out of their controller, which knock down a set of "penguins" when they collide.
   - **Estimated Challenge - 3:** Getting the physics right on this one could be tricky, as I have had some trouble with this in the past.
2. **Real-Life Anchoring**: Allows the carnival game to anchor itself to your real life space, increasing immersion, and making it seem like the arcade is build into your wall.
   - **Estimated Challenge - 5:** Getting this to work will be a real challenge, but I really want to give it a shot, the goal of this is to make it much more immersive, and to really transport the carnival to you.
3. **Prize Delivery System**: Knock down all the penguins? Get a prize!
   - **Estimated Challenge - 3:** I will have to implement some sort of script in order to properly get the game to detect when you have knocked down all the penguins, but once that is done, dropping a prize on the player should not be a huge challenge.
4. **Three Strikes And You're Out!**: Miss Three Balls? You loose, and the game resets!
   - **Estimated Challenge - 4:** This will be interesting, as I will have to know when the player has missed a penguin as well as when they have hit one, and take different actions accordingly while storing the value of the number hit and missed. Resetting the scene itself shouldn't be too hard, but the tricky part is re-initializing everything to the same location it was in at the start.

## Milestones

1. **By 11/19**:
   - Implement basic placement functionality to place the game in your room.
   - Add ball-shooting functionality to controller.
   - Add knocking down functionality to basic assets.
2. **By 12/5**:
   - Implement functionality to trigger a game reset.
   - Start on adding fanciful assets to make the game look polished
   - Implement Prize Delivery System.

## Inspirations

1. [Arcane - Target Practice Scene](https://youtu.be/-X0gU5-3HYo?si=O_tq56og8oZzpJBQ&t=54):
This scene with shooting paintballs at fake target creatures is largely the type of gameplay that I want to recreate with my project.
2. [Knock-Em-Down Carnival Game](https://www.pinterest.com/pin/carnival-games-diy--48343395992694432/)
The aestitic of my carnival game is aiming to match this classic carnival attraction. I could not find a good link showcasing it besides this Pinterest pin, so if I find a better example with more details I will update this part.