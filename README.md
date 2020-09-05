# Chess-Game
# Design Pattern - Factory Method

## version1

**Step1: Handling Ambiguity**
1. _Six W's:_
    #####a. Who is going to play this game: Any user who has interest in chess.
    #####b. What is the game about: A multi player chess game.
    #####c. Where the game is played: Command line
    #####d. When the game is played: When there are two players to play.
    #####e. How the game is played: By giving commands EX: H1 -> B1
    #####f. Why th user wants to play the game: To have fun!
    
2. How many players can play at a time: 2 (For now, may add a computer to play with the user).

**step2: Defining th core objects**

1. Board
2. Piece
3. Player
4. Move
5. Game
6. King
7. Queen
8. Bishop
9. Knight
10. Rook
11. Pawn

**step3: Analyze RelationShips**

1. Piece <- King
2. Piece <- Queen
3. Piece <- Bishop
4. Piece <- Knight
5. Piece <- Rook
6. Piece <- Pawn
7. Each **Game** has a **Board**
8. Each **Game** has two **Player**s
9. Each **Player** has a **Move**
10. Each **Board** has 2 **King**s, 2 **Queen**s, 4 **Bishop**s, 4 **Knight**s, 4 **Rook**s, 18 **Pawn**s

**step4: Investigate Actions**

1. Game:
    #####a. Creates a game with Board
    #####b. Create players
    
2. Board:
    #####a. Initializes the board
    #####b. checks if the cell in the board is available or not

3. Move:
    #####a. Moves piece from one position to other
    #####b. check movie is valid or not

4. Piece:
    #####a. Provide valid moves
    
    
*** 
**END OF THINKING CAPACITY(ETC) :p WILL UPDATE WHILE DEVELOPING**