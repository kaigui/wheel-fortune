# wheel-fortune
## Files or folders of interest
### Plans
Flow charts and pseudo code to start problem solving process
### wheel.ipynb
Jupyter Notebook file containing all python code
### csv files
r1_wheel.csv: Wheel data for Round 1

r2_wheel.csv: Wheel data for Round 2

test r1.csv: testing million space

test r2.csv: testing jackpot space

phrase_hint_list.csv: Example wheel of fortune phrases and hints from [https://wheeloffortuneanswer.com/phrase/]

## wheel.ipynb
The following python code simulates a game of Wheel of Fortune. The number of players and number of turns are automatically updated based on user input.

Functions are at located at the top of the file in individual modules. These functions include loading various csv files, simulating a random wheel spin, validating and checking guesses, manging vowel guesses, and running standard rounds of the game with variable numbers of players and turns. "Jackpot", "Million", "Bankrupt", "Lose Turn", and "Mystery" slots are also implemented.

This projects utilizes simple lists and indicies to handle turns, banks, eligiblity for million/jackpot, etc. 
