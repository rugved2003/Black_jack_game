# Black_jack_game
Black jack game 

This is a code for a simple text-based Blackjack game. Here's a description of the code:

The code begins by importing the random module, which is used for shuffling the deck and dealing cards.

The `deal_card` function randomly selects a card from a list of possible card values (11 for Ace, 2-10 for number cards, and 10 for face cards) and returns the chosen card.

The `calculate_score` function takes a list of cards as input and calculates the total score. It handles the special case of an Ace card, where it can be counted as either 1 or 11 depending on the total score. If the sum of the cards is 21 and the number of cards is 2, indicating a blackjack, it returns a score of 0.

The `compare` function compares the scores of the user and the computer and determines the outcome of the game. It considers various scenarios such as going over 21 (bust), having a blackjack, or having a higher score than the opponent.

The `play_game` function initializes empty lists for the user's and computer's cards. It then deals two cards to each player. It enters a loop where the user can choose to get another card or pass. The loop continues until the user goes bust, gets a blackjack, or decides to pass. After the user's turn, the computer takes its turn based on predefined rules. Finally, it prints the final hands and scores of both players and determines the winner using the `compare` function.

The code ends with a loop that asks the user if they want to play another game. If the user inputs 'y', a new game is started by calling the `play_game` function. Otherwise, the program terminates.

This code allows users to play multiple rounds of Blackjack with the computer as the dealer.
