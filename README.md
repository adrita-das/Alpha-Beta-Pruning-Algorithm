## Alpha-Beta Pruning Algorithm 

This repository contains an implementation and explanation of the Alpha–Beta Pruning Algorithm, an optimization technique for the Minimax algorithm used in game-playing artificial intelligence.

**What is Alpha–Beta Pruning?**

Alpha–Beta Pruning is a search algorithm (follow DFS) that improves the efficiency of the Minimax algorithm by eliminating branches of the game tree that cannot influence the final decision.

It is commonly used in:

- Chess

- Tic-Tac-Toe

- Checkers

- Other two-player, zero-sum games


**Key Concepts**

  - Minimax Algorithm: Determines the optimal move assuming the opponent plays optimally.

  - Alpha (α): The best value that the maximizing player can guarantee.

  - Beta (β): The best value that the minimizing player can guarantee.

  - Pruning: Discarding branches that do not affect the final outcome.

**Alpha–Beta Pruning Condition**

`α ≥ β`

This means further exploration of that branch is unnecessary.

## Advantages of Alpha–Beta Pruning

- Reduces time complexity

- Avoids unnecessary node evaluation

- Enables deeper searches in the same amount of time

- Produces the same result as Minimax

