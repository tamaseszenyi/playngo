# Test task - Chess tournament

There are 5 players at a chess tournament, where everyone plays 1 game with everyone else. Players get 2 points for a win, 1 for a draw, and 0 for a loss.

Here’s an example for the final scoreboard:
```
- A B C D E
A - 2 2 1 0
B 0 - 1 2 0
C 0 1 - 1 2
D 1 0 1 - 2
E 2 2 0 0 –
``` 
Explanation:
- Player A doesn’t play against themselves.
- Player A defeats player B, getting 2 points.
- Player A defeats player C, getting 2 points.
- Player A plays a draw with player D, getting 1 point.
- Player A loses to player E, getting 0 points.

## 1. Simulate a tournament, assuming that the outcomes are random. Log the results to the console.

Pay attention to the relationships between the games! For example, since player A has won against player B, player B’s row should indicate that they have lost to player A. Feel free to leave the player IDs from the log.

## 2. Log to the console who has won the tournament, and how many points they have reached

Here’s an example where Player B won the tournament with 7 points:
```
- A B C D E
A - 1 1 2 1
B 1 - 2 2 2
C 1 0 - 2 2
D 0 0 0 - 2
E 1 0 0 0 –
```
