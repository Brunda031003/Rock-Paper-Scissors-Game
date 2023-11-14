This repository contains a simple implementation of the classic Rock, Paper, Scissors game in Python. The game allows a user to play against the computer and keeps track of the number of wins for both the user and the computer. The user can choose to input their move as "rock," "paper," or "scissors," and the computer randomly selects its move. The winner of each round is determined based on the game's traditional rules: rock beats scissors, scissors beats paper, and paper beats rock.

Code Explanation:
random: The random module is used to generate a random number, allowing the computer to make a random selection between rock, paper, and scissors.

user_wins and computer_wins: These variables keep track of the number of wins for the user and the computer, respectively.

options: This list contains the possible moves: "rock," "paper," and "scissors."

The game runs in a loop (while True) until the user decides to quit by entering "Q."

User input is obtained using input(), and the input is converted to lowercase for case-insensitive comparison.

The computer's move is randomly selected from the options list.

The game outcome is determined based on the traditional Rock, Paper, Scissors rules, and the results are displayed to the user.

The loop continues until the user decides to quit. After quitting, the final scores for both the user and the computer are displayed.

Feel free to clone, modify, and enhance this simple Rock, Paper, Scissors game for your learning or entertainment purposes!
