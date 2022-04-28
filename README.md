# NumericalTicTacToe_ReinfL
Build an RL agent that learns to play Numerical Tic-Tac-Toe with odd numbers (the agent will always make the first move). 

We need to train the agent using Q-Learning. The environment is playing randomly with the agent, i.e. its strategy is to put an even number randomly in an empty cell. If the agent wins the game, it gets 10 points, if the environment wins, the agent loses 10 points. And if the game ends in a draw, it gets 0. Also, we want the agent to win in as few moves as possible, so for each move, it gets a -1 point.
