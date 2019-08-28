# checkers-with-gui
Checkers game developed in Java and Netbeans. 

The frontend is built in Java Swing. With features including:
* customize application appearance 
* multiplayer & singleplayer gamemodes (play vs computer / other human)
* saving / loading of games
* difficulty control of computer opponent

The backend is based on the classical AI minimax algorithm with alpha-beta pruning. Some optimizations are implemented based on domain-specific knowledge. 

Some examples of strategies used
* iterative deepening for time-limited search
* exploring in order of heuristic function for better efficiency

To do in the future:
* transposition table to spot repeated nodes
* quiescence detection
* beam search strategies
