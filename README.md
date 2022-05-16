# Blackjack (using Python)

### Introduction
This is a version of a conventional Blackjack game in Python.
The game is designed for two players (one player vs. the dealer (i.e. the computer)).

### Game objective
Both the player and the dealer can continue to request additional playing cards.
Both player and dealer should attempt to get a total score of as close to 21 as possible, without exceeding 21.

### Card values
Aces are worth either 1 or 11.
All face cards are worth 10.
Any other card is worth its numerical value.

### Game terminology
Hit: To 'Hit' is to ask for another card.
Stand: To 'Stand' is to hold the total and end the turn.
Bust: If the card total goes over 21, the player is bust, and the dealer wins regardless of the dealer's hand.
Dealing: Both player and dealer start with two cards, one of the dealer's cards is hidden until the end.

### Player's Turn
After the first round of dealing, each player has the option to hit (receive more cards) or stay (no more cards). If after the latest hit, the player goes bust (total going over 21), then the player loses the game.

### Dealer's Turn
When the player has finished their final hit, the dealer flips over the hidden card. If the dealer’s total is less than 17, then the dealer needs to hit (receive a new card). This process repeats until the dealer’s hand either totals 17 or more or busts (i.e. is above 21).

### To Run
Clone the repo: `git clone https://github.com/Paul72187/BlackjackPython.git`
Open the blackjack.py file and right click on it. Select "Run Python File in Terminal" to play the game in the terminal.
