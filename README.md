
### Chess Game (VS Computer)
![Screenshot](Screenshot.png)

1. **Piece Placement (8 ranks)**: This field represents the positions of the pieces on the board. Each rank is represented by a series of characters, where:
   - `K` represents a white king.
   - `Q` represents a white queen.
   - `R` represents a white rook.
   - `B` represents a white bishop.
   - `N` represents a white knight.
   - `P` represents a white pawn.
   - `k` represents a black king.
   - `q` represents a black queen.
   - `r` represents a black rook.
   - `b` represents a black bishop.
   - `n` represents a black knight.
   - `p` represents a black pawn.
   - Digits (1-8) represent empty squares, with the number indicating the count of consecutive empty squares.

   For example, `rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR` represents the starting position of a chess game.

2. **Active Color (1 character)**: This field indicates which player's turn it is to move. `w` represents White's turn, and `b` represents Black's turn.

3. **Castling Availability (1-4 characters)**: This field indicates whether castling is still available for each player. The characters used are:
   - `K` for White kingside castling.
   - `Q` for White queenside castling.
   - `k` for Black kingside castling.
   - `q` for Black queenside castling.
   - `-` if no castling is possible.

4. **En Passant Target Square (1-2 characters)**: If a pawn has just moved two squares forward from its starting position, this field represents the square where the opposing pawn can capture en passant. Otherwise, it is represented as `-`.

5. **Halfmove Clock (1-2 characters)**: This field represents the number of half-moves (ply) since the last pawn move or capture. It is used for the fifty-move rule.

6. **Fullmove Number (1-2 characters)**: This field represents the number of full moves (complete turns) in the game. It starts at 1 and is incremented after Black's move.

