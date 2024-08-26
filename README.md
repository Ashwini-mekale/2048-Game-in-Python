# 2048-Game-in-Python
   ![image](https://github.com/user-attachments/assets/ccbd72a7-6fff-4e6d-9fef-fd88e021d4ce)

# Introduction to the 2048 Game
2048 is a single-player puzzle game where you combine tiles with the same numbers.

1. Simple Rules
   Swipe left, right, up, or down to move tiles.

2. Combining Tiles
   Identical tiles merge into a tile with double the value.

3. Game Goal
   Reach the highest tile value possible.

# Game Mechanics and Objective
The game board is a grid of 4x4 tiles

| Number Tiles | game objects |
|--------------|--------------|
| 2,4,8,16     | Reach the highest possible tile value |
| Empty tiles  | New tiles spawn randomly |

# Implementing the Game Logic
Create a game board using a python list of lists.

| Generating Random Tiles | Moving Tiles | Updating the Board |
|--------------|--------------|------------------------|
|Randomly choose empty tiles to spawn a new tile with value 2 or 4| Shift tiles in the chosen direction, merging identical tiles | Update the game board after each move |
 

# Handling User Input
Use Keyboard input to control tile movement

## 1. key press detection
Detect Keyboard events for left,right,up,and down.

## 2. Move Tiles
Call the appropriate function to move tiles based on user input.

## 3. Update the Game 
Update the game board and score after each move

   ![image](https://github.com/user-attachments/assets/f06e89e4-96bf-49f9-a0e7-7e5b1bd37a2f)

# Checking for Game Over Conditions
The game ends when no valid moves are possible.


| No Empty  Tiles | No Mergeable Tiles |
|--------------|--------------|
| If all tiles are filled, and no further moves can be made.| If no adjacent tiles have the same value.|


![image](https://github.com/user-attachments/assets/ff294340-4dec-45d2-b82d-13f7ff78dcd5)


# Displaying the Game Score and High Score
Keep track of the player's score and high score.

![image](https://github.com/user-attachments/assets/8f7ae004-9ff2-48dd-8b24-9ab19eb040d8)
Game Score
Increase the score by the value of merged tiles.

![image](https://github.com/user-attachments/assets/2fd28bda-b3e1-4821-8013-ffbd93ba8d8b)
High Score
Store the highhest score achived


# Conclusion and Next Steps
You've created a functional 2048 game in python 

1. Enchancements
Add graphics, sound effects, and more features.

2. Multiplayer Mode
Implement a mode where two players compete.

3. AI Opponent
Develop an AI to play against the player.

   ![image](https://github.com/user-attachments/assets/0c989cd1-08ef-4c3b-b1e5-114f9b0a87e8)


# References

For detailed information on implementing 2048 game in python.
https://www.geeksforgeeks.org/2048-game-in-python/

   ![image](https://github.com/user-attachments/assets/733bcaa3-d3e4-4018-8bc9-6d89a7652d00)

