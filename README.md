# tic-tac-toe-AI
Tic-tac-toe AI using minimax

The Minimax algorithm is a decision-making technique based on the Maximizer vs. Minimizer concept. In a game like Tic-Tac-Toe, the goal of the AI (Maximizer) is to maximize its chances of winning, while the opponent (Minimizer) tries to minimize their loss.


How Minimax Works in Tic-Tac-Toe?

Minimax evaluates every possible move by simulating the game’s future states. It determines the optimal move by assigning a utility value to each possible outcome. The utility function measures how favorable a final game state is:

Win for AI → High positive score
Loss for AI → High negative score
Draw → Neutral score (usually 0)
The AI explores all possible moves, predicts the opponent's best responses, and chooses the move that maximizes its advantage while minimizing the opponent's chances.


Why Use Minimax?
Guaranteed optimal moves: It ensures the best possible move is chosen.
No randomness: The AI always plays perfectly.
Predicts opponent’s strategy: By assuming the opponent also plays optimally, Minimax makes strong decisions.
To learn more about the Minimax algorithm, refer to this link 

https://www.geeksforgeeks.org/minimax-algorithm-in-game-theory-set-1-introduction/
