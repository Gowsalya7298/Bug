****Files overview*****
app.py runs tic-tac-toe using the standard minimax algorithm
a_b_prune.py runs the game using optimised Alpha-beta-prunning.

****Installations Required*****
Python 3.x, no other installations are required.

****To run the game******
1. Open powershell or command prompt in the current directory.
2. To run game using minimax algorithm, run:
    >python app.py
3. To run the game using alpha beta prunning, run:
    >python a_b_prune.py

****Changing between Tic-tac-toe & 5-in-a-row*****
1. in both the files, changing the values of two variables, will make the respective
   algorithms run on tic-tac-toe/5-in-a-row.
2. The two variables are "size" (line no.9) and "win_moves" (line_no.12).
3. The configurations of the two variables to run either one of the games are:
    3.1) to run tic-tac-toe:
        size=3,win_moves=3
    3.2) to run 5-in-a-row:
        size=15,win_moves=5