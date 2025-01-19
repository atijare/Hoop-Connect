# Blackjack Game

This is a simple graphical Blackjack game implemented in Python using the Tkinter library. The game allows a player to compete against the dealer with traditional Blackjack rules.

## Features

- **Interactive Gameplay**: Hit or stand with buttons to interact with the game.
- **Dealer AI**: Dealer automatically follows Blackjack rules (hits until score is 17 or more).
- **Card Graphics**: Displays cards using image files.
- **New Game and Shuffle Options**: Start a new game or shuffle the deck at any time.

## How to Play

1. **Objective**: Achieve a hand value closer to 21 than the dealer without going over (busting).
2. **Game Flow**:
   - Click **Player** to draw a card.
   - Click **Dealer** to let the dealer play their turn.
   - Click **New Game** to reset the game.
   - Click **Shuffle** to shuffle the deck.

## Requirements

- Python 3.6 or higher
- Tkinter (comes pre-installed with most Python distributions)
- Card images stored in the `cards/` directory in PNG or PPM format.

### Card Image Format

Ensure your card images are organized as follows:
cards/ 1_heart.png 2_heart.png ... jack_spade.png queen_spade.png king_spade.png
