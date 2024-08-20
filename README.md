# Blackjack Game

## Overview

Welcome to the Blackjack Game! This simple web-based game allows you to play a round of Blackjack, also known as 21, directly in your browser. The goal is to get as close to 21 as possible without going over. You can draw new cards and see if you can beat the house!

## Features

- **Player Input**: Enter your name to start the game and see your current chips balance.
- **Interactive Gameplay**: Draw new cards to get closer to 21.
- **Game Status**: The game will let you know if you've won (Blackjack!), lost (over 21), or if you should draw another card.
- **Help Section**: A help modal is available to guide you on how to play the game.

## How to Play

1. **Enter Your Name**: Type your name in the input field.
2. **Start the Game**: Click the "Start Game" button to begin. You'll receive two cards, and their sum will be displayed.
3. **Draw New Cards**: If your sum is below 21, you can choose to draw a new card by clicking the "NEW CARD" button.
4. **Win or Lose**: If your sum is exactly 21, you win the round! If it exceeds 21, you lose the game.
5. **Help**: Click the "Help" button for a quick guide on how to play.



## Files

- `index.html`: The main HTML file that structures the game.
- `index.css`: The stylesheet for styling the game.
- `index.js`: The JavaScript file containing the game logic.

## Game Logic

The game follows the standard rules of Blackjack:

- The player starts with two random cards.
- Cards 2-10 are worth their face value.
- Face cards (Jack, Queen, King) are worth 10.
- An Ace is worth 11 (but can be adjusted if it causes the sum to exceed 21).
- The player can draw additional cards to try and get as close to 21 as possible without going over.
- If the player's sum is exactly 21, they win. If it's over 21, they lose.
