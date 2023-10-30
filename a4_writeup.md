# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
Thinking through how to figure out if a player has won was definitely the hardest part. The entire time, I was overcomplicating the process and I was trying to write the best and most compact code possible which slowed me down and confused me. I was also mixing up board indices while trying to figure out how to loop over the columns and the rows of the board.

2. Explain how you would add a computer player to the game.
I would write a function called "AI" that would be assigned whatever character the player didn't close and simply pick a random spot on the board that wasn't occupied. This is the most simple AI possible but I remember watching a video on a Tic Tac Toe AI and it was a bit advanced and complicated which involved using trees to look at every move and determine which move is better than another.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
You would have to give a score to each move and make the computer pick the highest score possible. To do this, you have to consider what the player and the computer can do after each move and calculate the scores for each move as well. This is a very simplistic explanation as I seen that video a while ago and I don't think I can implement it on my own without some help.