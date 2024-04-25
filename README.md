# Blackjack_game

The provided Blackjack program is a console-based game where the player competes against a computer-controlled dealer. It allows the player to hit (take another card) or stand (keep the current hand) in an attempt to achieve a hand sum as close to 21 as possible without exceeding it. The game includes features such as random card distribution, hand sum calculation, win/lose conditions, error handling for maximum card limit, user interaction via console input, and clear output messages indicating game state and outcomes.

Features of this program
1. Player vs. Dealer: The game simulates a player competing against a dealer.
2.Initialization: The game starts with both the player and the dealer having two cards each.
3.Random Card Distribution: Cards are distributed randomly to both the player and the dealer. Each card's value ranges from 1 to 11.
4.Sum Calculation: The game calculates the sum of the cards in the player's and dealer's hands.
5.Game Flow: The game proceeds with the player deciding whether to "hit" (take another card) or "stand" (keep the current hand) until the player decides to stand or their hand exceeds 21.
6.Dealer's Turn: After the player's turn, if the dealer's hand sum is less than 17, the dealer automatically takes another card until their hand sum reaches 17 or more.
7.Win/Lose Conditions:
If either the player or the dealer reaches a hand sum of 21 (blackjack), they win.
If a player's hand sum exceeds 21, they lose.
If both the player and the dealer stand, their hands are compared, and the one with the higher sum wins. If their sums are equal, it's a tie.
8.Error Handling: The game handles situations where a player tries to hit beyond the maximum allowed cards (5) and appropriately notifies the player.
9.User Interaction: The game prompts the player with options to hit or stand and takes input accordingly using cin.
10.Output: The game provides clear output messages to the player, indicating game state and outcomes.
Overall, the implemented Blackjack game provides a basic but functional simulation of the popular card game, allowing players to play against a computer-controlled dealer and experience the thrill of trying to get as close to 21 as possible without going over.
