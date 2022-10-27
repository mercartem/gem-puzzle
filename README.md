# [Gem puzzle](https://mercartem.github.io/gem-puzzle/gem-puzzle/dist/)

## Task

You are to implement a classic game — [Gem Puzzle](https://en.wikipedia.org/wiki/15_puzzle)

### Game rules

`Game is a sliding puzzle that consists of a frame of numbered square tiles in random order with one tile missing. The puzzle also exists in other sizes, particularly the smaller 8-puzzle. If the size is 3×3 tiles, the puzzle is called the 8-puzzle or 9-puzzle, and if 4×4 tiles, the puzzle is called the 15-puzzle or 16-puzzle named, respectively, for the number of tiles and the number of spaces. The object of the puzzle is to place the tiles in order by making sliding moves that use the empty space.`

### Approximate appearance

![](https://i.imgur.com/yaunqVV.png)

### Main functional requirements

`Basic (required):`

- the design should be responsive, that includes *desktop(1280px <= width)*, *tablet(768px <= width < 1280px)* and *mobile(320px <= width < 768px)*. When switching between versions everything should be displayed correctly, all functionality should be present, nothing should disappear or leave beyond the screen. It is acceptable to change the appearance for the mobile version (for example, hide the buttons in the burger menu)
- initially, `body` in the index.html file must be empty, all necessary elements are generated using JS
- the default size of the frame is 4x4
- at the beginning state of the game, the frame is filled with randomly generated numbers, when starting a new game, numbers are re-shuffled randomly
- when you click on a tile next to an empty cell, the tile moves to the empty cell

`Advanced:`

- the game can be restarted without reloading the page
- display the game duration in minutes and seconds "##:##" and the number of moves
- implement the functionality to save the game (for example, using localStorage), so that when the page is reloaded, a player can continue from where he left off
- it is possible to turn on / off the sound accompaniment of the movement of tiles
- implement functionality to choose frame size: from 3х3 to 8х8
- the top 10 results are saved in the high score table and can be viewed in any way (for example, by pressing a button)

`additional (to get extra points):`

- tiles can be dragged to an empty cell with the help of mouse
- on a successful game solution, display the message: «Hooray! You solved the puzzle in ##:## and N moves!»
- implement animation moving tiles on the field
