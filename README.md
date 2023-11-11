# Rock-paper-and-scissors-game
# Algorithm :
Import the random module
Initialize the global variables for choices as a tuple of r, p, s, and computer score and player score as 0.
Create a function for getting the player’s choice.
Inside the function get the input from the user.
Check if the input is valid, If yes then return the answer to the function call. If no, then return the function call so that it will again ask for input from the user.
Create a function to return the computer’s choice as input from the random. choice function.
Create a game function inside which we will check who scores the mount for the current game.
Call the player’s choice function and save the answer in a variable.
Call the computer choice function and save it in another variable.
Now, check if both the answers are the same, if so then print its a tie and no one gets a point.
Following are the scenarios where the player gets a point,
Player choice- “r” computer choice- “s”
Player choice- “s” computer choice- “p”
Player choice- “p” computer choice- “r”
In all the other conditions computer scores a point.
Now, print both the points to the user.
Now, in our main part of the program, we need to write a welcome message.
Call the game function 4 times for running the game for 4 rounds.
Ask the user if the user wants to continue/ reset and continue/quit.
If the user wants to continue repeat step 7.
If the user wants to reset and continue re-declare the variables for player score and computer score to zero and repeat step 7
If the player wants to quit you can print thank you for playing and exit the game.
# Note :
The lower() method converts the input given by the user to lowercase. 
Global variables are used to increase the scope of the variable throughout the function. To know more about global variables, Global Variables
Recursion is the process of calling the same function inside the function definition. To know about recursion, recursion.
# outline
We will ask the user to select either rock paper or scissors. And we will also make the computer choose one out of three randomly.
Now we will check who won the game and give them a score.
This is done 5 times to say who has won finally and we will ask the user if they want to continue or reset and continue or exit the game.
