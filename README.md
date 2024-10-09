# LISP Game Project

## Bug Report
- There is a validation issue when selecting a piece. Inputting selections like "AP" and "A10" cannot be parsed correctly.

## Feature Report
- AI/Helper/Strategies implemented
- Score and win calculations
- Round wins and score display
- Win condition logic
- Option to continue playing based on wins
- Player prompt for another round

## Data Structures
- **Game State**: Manages the board, player scores, and wins.
- **Player List**: Tracks the order of players, distinguishing between human and computer players, and assigns colors.

## Development Log

### 2/29 - Input Validation
- Set up validation for user input, checking size, number, and letter ranges.
- **Functions Created**: `user-input`, `inputValidation`, `check-letter`, `check-number`.
- **Time Spent**: 3 hours.

### 3/1 - Coin Toss Setup
- Implemented coin toss for player selection but not yet assigning color or current player.
- **Functions Created**: `coin-toss`, `binary-input-validation`.
- **Time Spent**: 1 hour.

### 3/2 - Game State Initialization
- Initialized game state, default scores, and board setup. Added board display functionality.
- **Functions Created**: `printboard`, `initialize-game-state`, etc.
- **Time Spent**: 2 hours.

### 3/2 - Menu and Player Swapping
- Implemented game menu and player swapping without using `setq/setf`.
- **Functions Added**: `game-menu`, `startgame`, `swap-player`.
- **Time Spent**: 2 hours.

### 3/4 - Validation Updates and Position Conversion
- Enhanced validation to ensure the selected piece matches the current player's color.
- **Functions Added**: `getrow`, `getpiece`, `check-selection`, `convert-input`.
- **Time Spent**: 2 hours.

### 3/5 - Movement Validation
- Started validating horizontal piece movements.
- **Functions Created**: `check-for-block`, `reverse-list`, `horizontal-check`.
- **Time Spent**: 2 hours.

### 3/6 - Vertical and Diagonal Movement
- Implemented vertical and right diagonal checks for movement validation.
- **Functions Created**: `vertical-check`, `startposition`.
- **Time Spent**: 2 hours.

### 3/7 - Diagonal Movement Fixes
- Added functions to validate right and left diagonal movements.
- **Functions Created**: `rightdiagonal-check`, `leftdiagonal-check`.
- **Time Spent**: 2 hours.

### 3/8 - Movement Display
- Implemented functions to display all possible moves for a piece.
- **Functions Created**: `displayallpossiblemoves`, `find-all-positions`.
- **Time Spent**: 2 hours.

### 3/9 - Serialization and Save Game
- Added file validation for serialization and save game functionality.
- **Functions Created**: `savegame`, `formatforsavegame`, `prompt-for-valid-filename`.
- **Time Spent**: 2 hours.

### 3/10 - Board Updates
- Updated board state based on piece movements.
- **Functions Created**: `replace-element-at`, `updateboard`.
- **Time Spent**: 2 hours.

### 3/11 - Win Condition Logic
- Implemented a flood fill algorithm for checking win conditions.
- **Functions Created**: `floodwin`, `neighboring-pieces`, `allpiecesconnected`.
- **Time Spent**: 2 hours.

## Screenshots
_(Add screenshots here)_
