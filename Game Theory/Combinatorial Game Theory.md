Combinatorial games are two-person games with perfect information and no chance moves (no randomization like coin toss is involved that can effect the game). These games have a win-or-lose or tie outcome and determined by a set of positions, including an initial position, and the player whose turn it is to move. Play moves from one position to another, with the players usually alternating moves, until a terminal position is reached. A terminal position is one from which no moves are possible. Then one of the players is declared the winner and the other the loser. Or there is a tie (Depending on the rules of the combinatorial game, the game could end up in a tie. The only thing that can be stated about the combinatorial game is that the game should end at some point and should not be stuck in a loop. In order to prevent such looping situations in games like chess(consider the case of both the players just moving their queens to-and-fro from one place to the other), there is actually a “50-move rule” according to which the game is considered to be drawn if the last 50 moves by each player have been completed without the movement of any pawn and without any capture. [Source : Stackexchange] 

On the other hand, Game theory in general includes games of chance, games of imperfect knowledge, and games in which players can move simultaneously. 

The specialty of Combinatorial Game Theory (CGT) is that the coding part is relatively very small and easy. The key to the Game Theory problems is that hidden observation, which can be sometimes very hard to find. 

Chess, Game of Nim, Tic-Tac-Toe all comes under the category of Combinatorial Game Theory. 

We can divide these games into two categories as shown below:
![image](https://user-images.githubusercontent.com/67746411/182773033-a4673d6e-cd02-4787-8839-1d3c4bac3252.png)
The difference between them is that in Impartial Games all the possible moves from any position of game are the same for the players, whereas in Partisan Games the moves for all the players are not the same. 

Consider a game like below: 

Given a number of piles in which each pile contains some numbers of stones/coins. In each turn, player choose one pile and remove any number of stones (at least one) from that pile. The player who cannot move is considered to lose the game (ie., one who take the last stone is the winner). 

As it can be clearly seen from the rules of the above game that the moves are same for both the players. There is no restriction on one player over the other. Such a game is considered to be impartial. 

The above mentioned game is famous by the name- Game of Nim which will be discussed in next sections. 

In contrast to the above game, let us take an example of chess. In this game, one player can only move the black pieces and the other one can only move the white ones. Thus, there is a restriction on both the players. Their set of moves are different and hence such a game is classified under the category of Partisan Games. 

Partisan Games are much harder to analyze than Impartial Games as in such games Sprague-Grundy Theorem fails. 

In the next sections, we will see mostly about Impartial games, like- Game of Nim and its variations, Sprague-Grundy Theorem and many more. 

Exercise: Readers may try solving below simple combinatorial Game Theory problems. 

Cycle Race 

Game of Chocolates 

Sources: 

http://www.cs.cmu.edu/afs/cs/academic/class/15859-f01/www/notes/comb.pdf 

https://en.wikipedia.org/wiki/Combinatorial_game_theory 

https://en.wikipedia.org/wiki/Impartial_game 

https://en.wikipedia.org/wiki/Partisan_game 
