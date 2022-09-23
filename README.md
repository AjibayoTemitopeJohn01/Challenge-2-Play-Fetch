# Challenge 2-Play-Fetch
This repository is a collection of tutorials from https://learn.unity.com/course/create-with-code

# Challenge 2 - Play-Fetch
## Summary
## Challenge Overview: 
Use your array and random number generation skills to program this challenge where balls are randomly falling from the sky and you have to send your dog out to catch them before they hit the ground. To complete this challenge, you will have to make sure your variables are assigned properly, your if-statements are programmed correctly, your collisions are being detected perfectly, and that objects are being generated randomly. 

### Challenge Outcome:
- A random ball (of 3) is generated at a random x position above the screen.
- When the user presses spacebar, a dog is spawned and runs to catch the ball.
- If the dog collides with the ball, the ball is destroyed.
- If the ball hits the ground, a “Game Over” debug message is displayed.
- The dogs and balls are removed from the scene when they leave the screen.

## Materials
- Challenge 2 - Starter Files.zip

### Challenge Objectives:
In this challenge, you will reinforce the following skills/concepts:
- Assigning variables and arrays in the inspector.
- Editing colliders to the appropriate size.
- Testing xyz positions with greater/less than operators in if-else statements.
- Randomly generating values and selecting objects from arrays.

## 1. Challenge Instructions:
- Open your Challenge 2 project.
- Download the " Challenge 2 Starter Files" from the Tutorial Materials section, then double-click on it to Import.
- In the Project Window > Assets > Challenge 1 > Instructions folder, use the "Challenge 2 - Instructions" and “Outcome” video as a guide to complete the challenge.

## 2. Warning
When you import the challenge into your project, it is supposed to have bugs. 
The purpose of the challenge is for you to fix those bugs, which are listed below. There are also hints at the bottom of the page to help you if you get stuck.
If you cannot fix the bugs and wish to delete the challenge files from your project, in the Project window, right-click on Assets > Challenge 1 and select Delete. 
Good luck!

## 3. Dogs are spawning at the top of the screen
Make the balls spawn from the top of the screen.

## 4. The player is spawning green balls instead of dogs
Make the player spawn dogs. 

## 5. The balls are destroyed if anywhere near the dog
The balls should only be destroyed when coming into direct contact with a dog.

## 6. Nothing is being destroyed off screen
Balls should be destroyed when they leave the bottom of the screen and dogs should be destroyed when they leave the left side of the screen.

## 7. Only one type of ball is being spawned
Ball 1, 2, and 3 should be spawned randomly.

## 8. Bonus: The spawn interval is always the same
Make the spawn interval a random value between 3 seconds and 5 seconds.

## 9. Bonus: The player can “spam” the spacebar key
Only allow the player to spawn a new dog after a certain amount of time has passed.

## OPTIONAL STEP
## Hints
- Make the balls spawn from the top of the screen
Hint - Click on the Spawn Manager object and look at the “Ball Prefabs” array.
- Make the player spawn dogs 
Hint - Click on the Player object and look at the “Dog Prefab” variable.
- The balls should only be destroyed when coming into direct contact with a dog
Hint - Check out the box collider on the dog prefab.
- Balls should be destroyed when they leave the bottom of the screen and dogs should be destroyed when they leave the left side of the screen
Hint - In the DestroyOutOfBounds script, double-check the lowerLimit and leftLimit variables, the greater than vs less than signs, and which position (x,y,z) is being tested.
- Ball 1, 2, and 3 should be spawned randomly
Hint - In the SpawnRandomBall() method, you should declare a new random int index variable, then incorporate that variable into the Instantiate call.
- Bonus - Make the spawn interval a random value between 3 seconds and 5 seconds
Hint - Set the spawnInterval value to a new random number between 3 and 5 seconds in the SpawnRandomBall method.


© Unity 2022 Challenge 2 - Play-Fetch.
