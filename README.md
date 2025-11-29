# Nine Men's Morris

Nine men's morris is a strategy board game for two players, dating back to at least the Roman Empire. The game is also known as *nine-man morris, mill, mills, the mill game, merels, merrills, merelles, marelles, morelles, and ninepenny marl* in English. In North America, the game has also been called cowboy checkers, and its board is sometimes printed on the back of checkerboards. Nine men's morris is a solved game, that is, a game whose optimal strategy has been calculated. It has been shown that with perfect play from both players, the game results in a draw.

## Game Rules
The board consists of a grid with twenty-four intersections, or points. Each player has nine pieces, or men, usually colored black and white. Players try to form 'mills'—three of their own men lined horizontally or vertically—allowing a player to remove an opponent's man from the game. A player wins by reducing the opponent to two men (whereupon they can no longer form mills and thus are unable to win) or by leaving them without a legal move.

The game has three phases:
- Placement phase (i.e., opening game)
- Moving phase (i.e., mid-game phase)
- Flying phase (i.e., end-game phase)

### Phase 1: Placement Phase
The game begins with an empty game board. For this desktop application, **white player** starts first and then black player is second. The white player is the human player and the black player is the AI. During the placement phase, both players have 9 game pieces which they take turns to place a piece on an empty spot. *If a player is able to place three pieces on contiguous points in a straight line, vertically or horizontally, they have formed a mill, which allows them to remove one of the opponent's pieces from the board*. A piece in an opponent's mill, however, can be removed only if no other pieces are available. After all men have been placed, phase two (i.e., moving phase) begins.

### Phase 2: Moving Phase
Players continue to alternate moves, this time moving a piece (based on their color) to an adjacent point each turn. A piece may not "jump" another piece. Players continue to try to form mills and remove the opponent's pieces as in phase one. If all of a player's pieces get blocked in (where they are unable to move to an adjacent, empty space) that player loses. A player can "break" a mill by moving a piece out of an existing mill, then moving it back to form the same mill a second time (or any number of times), each time removing one of the opponent's men. The act of removing an opponent's man is sometimes called "pounding" the opponent. When one player has been reduced to three men, phase three (i.e., flying phase) begins. **NOTE:** There is no limit to the number of mills that can be formed on the game board.

### Phase 3: Flying Phase
When a player is reduced to three pieces, there is no limitation for the player with 3 pieces on moving to only adjacent points: The player's piece may "fly" (or "hop", or "jump") from any point to any vacant point. **NOTE:** When the player's total pieces on the game board is reduced to less than 3, the game ends immediately and that player losses the game.


## Application Instruction
- Make sure you have JDK 25 installed on your computer. If not, you can install the lastest and most stable version of Java by visiting Microsoft JDK link - https://learn.microsoft.com/en-us/java/openjdk/download
- Download the *.jar* file in this repository.
- Double click the application to open it to start playing.
- The game board positions are array index. Meaning that the board starts from position 0 and ends at position 23. This will be useful when the human player needs to remove a black piece after forming a mill. *See the screenshot below*.

<img width="1824" height="2010" alt="image" src="https://github.com/user-attachments/assets/05c01857-5b80-4940-89ab-1e158b905aeb" />
