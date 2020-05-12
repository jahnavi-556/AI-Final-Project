# Final Project
## Comparison of Tic-tac-toe Game with Minmax algorithm and Q-Learning Algorithm
### Introduction

*	Tic-tac-toe also known as noughts and crosses or X’s and O’s is a two players game in which player can choose either X or O, who take turns marking the spaces in a 3×3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner.
* Tic-Tac-Toe game is written in Python and pyGame. You can play versus the computer.
*	We implement tic-tac-toe by using both Minmax and Q-learning Algorithms.

### Goal of the project
*	The main goal of the project is to compare the tic tac toe game using 2 algorithms
Minmax Algorithm and Q-learning Algorithm
*	By evaluating both the algorithms considering the complexity of code and time taken to complete as the key factors. Finally, we will select the best Algorithm to implement the tic tac toe game

### Minmax Algorithm
<h3 align="center">
<img src="MinmMax Algorithm.png" width="400">
 </h3>   
 
As shown in the figure the maximiser and minimizer are two recursive functions which accepts the state as a variable.
In the maximizer it first checks whether the state is terminal state i.e end state then it return its utility.
If the state is not terminal state it *Define v as negative infinity and  it call its’s own function for the v by passing result of next possible state and action.
* The loop continues until it reaches the terminal state
* The same thing going to happen in maximiser recursive function except defining v as positive infinity for the maximiser.




### Q-learning Algoritm
<h3 align="center">
<img src="Q-learning Algorithm.png" width="500" height="400">
</h3> 
                                               
### Winnings Of Minmax
<img src="Minmax winnings.PNG" width="600" height="400">

### Winnings of Q-learning Algorithm
<img src="Q learning winning.PNG" width="600" height="400">

### Comparosion of Results ( MinmMax vs Q-learning)
<img src="Comparision.png.PNG" width="600" height="400">

### Results 
Minmax Algorithm is the best algorithm for the implementation of the Tic-Tac-Toe game. As the time taken to complete the game is less and it gives tough competition to the user.
