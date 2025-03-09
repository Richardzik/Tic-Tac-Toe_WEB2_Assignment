# Tic-Tac-Toe_WEB2_Assignment

Tic-Tac-Toe is a project that features two implementations of the tic-tac-toe classic game. One using Object-Oriented Programming principles and the other one Functional Programming paradigms. Both versions offer an identical user experience, allowing players to enjoy the game seamlessly.

## How to play

1. Open eiher `oo.html` (OOP version) or `fun.html` (FP version) in your web browser.
2. The game starts with **X turn**. 
3. Click on an empty cell to place the first symbol.
4. Players alternate turns until:
    - A player wins by forming three of their symbols in a row, column, or diagonal.
    - The board fills up, resulting in a draw
5. Click the **Reset** button at any time to restart the game 

## Features

- **Two Programming Approaches**: Play the game implemented using OOP or FP principles.
- **Real-time Game Status**: Displays whose turn it is, announces the winner or concludes the draw.
- **Reset Functionality**: Allows players to restart the game at any moment.
- **Efficient Move Validation**: Ensures only valid moves are made.

## Implementation details

### Object-Oriented Version
- Uses classes for implementing game logic and generating board.
- Maintains game state by changing it through class properties.
- Separates concerns between Board and Game classes.
### Functional Programming Version
- Uses pure functions for game logic
- Make use of `reduce.` and `filter.` functions
- Maintains game state by returning the new state of the game instead of changing it.

Enjoy playing Tic-Tac-Toe 😁!


