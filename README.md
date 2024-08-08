# Connect4-with-AI #

## Overview

Connect Four is a classic two-player board game where the objective is to connect four of your own discs in a row, either horizontally, vertically, or diagonally. This implementation of Connect Four in C# provides a console-based user interface and supports two modes of play:
* Two Players: Play against another person.
* Against Computer: Play against an AI using the Minimax algorithm.

## Features

* **Interactive Console UI**: User-friendly console interface for playing the game.
* **Minimax AI**: Intelligent computer opponent for single-player mode.
* **Dynamic Board Size**: Choose the board dimensions between 4x4 and 8x8.
* **Score Tracking**: Keeps track of scores for both players.
* **Game Status**: Detects game over conditions and checks for board fullness.
* **Replay Option**: Allows restarting the game or quitting after it ends.

## Code Structure

**GameLogic**: Contains the core logic for the game.

**BoardGameManager**: Manages the game board, player moves, and game state.

**GameScores**: Tracks scores for both players.

**eShapes, ePlayer, eGameType**: Enums for game pieces, players, and game modes.

**GameUi**: Manages the user interface and game flow.

**ConnectFourUI**: Handles user input, displays the board, and manages game interactions.

**Project2**: The entry point of the application.

**Program**: Starts the game by initializing the ConnectFourUI.
