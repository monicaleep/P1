TODO

- [x] Grid to represent the board - array of arrays. 0 represents empty, 1 represents occupied
- [ ] Initial size: 20 rows, 10 columns
- [x] render the grid to DOM, give each square an ID
- [x] Pieces - a class,  a shape, an offset
- [x] offset determines the top left corner of the piece
- [x] piece gets initially placed at top row, halfway across.
- [x] board is an object, with piece instance attached
- [x] event listeners - l/r check for walls,
- [ ] check for pieces already placed,
- [x] update piece offset (rerender)
- [x] event listeners - down, check for piece or bottom, set piece to become part of board
- [ ] gravity - same as event listener for down but happens every 5 sec.
- [x] check board for full rows every time piece is "placed" into the board
- [x] clear a full row, maybe use splice and then place a new empty row at the beginning of the board? rerender board. Need to check for multiple rows cleared at once.
- [x] board generates a random piece each time a piece is placed
- [ ] game over when piece cannot move or cannot even be generated to the board.
- [ ] update score on DOM
- [ ] handle piece rotation
