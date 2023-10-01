# CSC133-Fall2023-Program-07-1
Simple Games, Inc., has contracted Wizard of Oz Solutions to create a command-line, interactive Rock-Scissors-Paper program to be marketed across the globe.
A graphical, online version can be seen at:  http://playrps.com/

![image](https://github.com/bryanosborne/CSC133-Fall2023-Program-07-1/assets/22990921/edaa7d9c-0843-4638-a864-c13186a3f2a6)

The program must:
 - Follow the rules of the game
  - Rock smashes Scissors
  - Scissors cuts Paper
  - Paper covers Rock
 - Provide appropriate prompts to the user with instructions and game outcomes
 - Allow the user to keep playing until they indicate otherwise
 - Keep score and display wins/losses after each turn

You may only use what we have studied so far in class.  But, having only learned while loops, if statements, and how to work with numbers, we actually have all we need to write this program!

Create pseudocode first and then use it for your comments.

Additional information:
Retrieve the user’s move by requesting a number, i.e., 
  print(“Enter your play: 0 for Rock, 1 for Paper, or 2 for Scissors”)
  userMove = int(input()) 
The computer will need to generate a random number from 0 to 2 for its move.  This can be done with the random function.  For example, the following will generate a 0, 1, or 2:
  computerMove = random.randint(0,2)
Then to see who won, just compare the “moves”. 
To check if the user wishes to continue play, refer back to the GPA averaging program written in class

![image](https://github.com/bryanosborne/CSC133-Fall2023-Program-07-1/assets/22990921/fd06b75e-f2e0-4a44-bad1-fbc9a2d3de73)


