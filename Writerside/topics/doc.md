# Ilmarinen project Requirements

## Minimum requirements

### Widgets required
* Chessboard
* Chess Engine
* Notation
* Opening Tree
* Database (PGN)
* chess.com/lichess APIs for Opening Tree / Database 
* chess.com/lichess export-last-game
* Clipboard handler(?)


### Per-widget Requirements

#### Chessboard
- [ ] supports ctrl+v of FEN type
- [ ] support manual position entry (sub-widget of another board with buttons for FEN metadata)
- [x] board 
- [x] board resizing doesn't break it
- [x] moves are validated when made
- [ ] attachment to notation widget logic.

#### Chess Engine
- [ ] add support for Leela
- [x] Engine Infinite Analysis
- [ ] parsing evaluation better

#### Notation
- [ ] Display current game move history
- [ ] Allow variations
- [ ] Allow commentary
- [ ] Make variartion UI not COMPLETELY shit

#### Opening tree