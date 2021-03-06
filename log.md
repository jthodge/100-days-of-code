# 100 Days Of Code - Log

### R1D1: 2018-06-06

**Today's Progress**: Invested ~1 hour into building Tic Tac Toe for my Recurse Center application. Using Canvas, constructed the board and implemented player marking in board spaces. Tomorrow I'll tackle the win condition logic.

**Thoughts:** No difficulties encountered in coding today since I'm famililar with the JS and Canvas needed today.  (Though I'm certain this lack of difficulty will change soon enough...) Feelings of warmth and support from the 100 Days of Code community members are bolstering, and it's lovely to be apart of such a welcoming and inviting space.

**Link to work:** [Tic Tac Toe repo](https://github.com/jthodge/tic-tac-toe)

### R1D2: 2018-06-07

**Today's Progress**: The code I wrote yesterday smelled terrible so I invested my time today in refactoring it. I cleaned the global namespace by placing all loose variables in a general function called via a public API, and I generalized a couple of single-purpose functions. Everything is much cleaner, which will make it much easier to implement win conditioning.

**Thoughts:** Progress today was slow, but fruitful, as refactoring forced me to slow down and really consider how each function interacts with the others.

**Link to work:** [Tic Tac Toe repo](https://github.com/jthodge/tic-tac-toe)

### R1D3: 2018-06-08

**Today's Progress**: Found a better way to determine move position, as well as a cute method of updating the current board state of a game. Currently thinking of ways to push drawn moves the updated board state...

**Thoughts:** Taking moves drawn to the canvas and pushing them to an updated board state is proving to be more difficult than I anticipated, which I'm feeling frustrated about. Waiting until so late into the day (night) definitely makes my thinking sluggish, so I'm eager to rethink this when I'm fresh.

**Link to work:** [Tic Tac Toe repo](https://github.com/jthodge/tic-tac-toe)

### R1D4: 2018-06-09

**Today's Progress**: Took a while of staring into space to arrive at using the 'mousemove' event position to determine row and column location, and then updating the board state based this location. Tomorrow is (finally!) win condition logic.

**Thoughts:** Waiting until late at night to code is a habit that I'm finding unproductively frustrating. Shifting this practice to another location in the day would probably speed up progress on this project. I'm ready to ship it and move on to something else.

**Link to work:** [Tic Tac Toe repo](https://github.com/jthodge/tic-tac-toe)

### R1D5: 2018-06-10

**Today's Progress**: Slow day today. Implemented win condition logic for verticals, horizontals, and diagonals. Ran into issues with setInterval(); and a couple of Canvas fill functions covering drawn moves, but quickly resolved them. 

**Thoughts:** Proud that I managed to carve out time today, and reminding myself that a small amount of progress is still progress.

**Link to work:** [Tic Tac Toe repo](https://github.com/jthodge/tic-tac-toe)

### R1D6: 2018-06-11

**Today's Progress**: Today was one those days where you spend a couple of hours debugging, only to step away for a bit, come back, and realize that 13 lines needed to be indented. 

**Thoughts:** A bit frustrated, and a whole lot relieved.

**Link to work:** [Tic Tac Toe repo](https://github.com/jthodge/tic-tac-toe)

## R1D8: 2018-06-13

**Today's Progress**: Made decent progress today by implementing Win and Tie notifications. Tie is a bit rough around the edges and I'd like to make it pleasing to the eye. For now, it's functional though!

**Thoughts:** Ready to put the finishing touches on and ship this thing!

**Link to work:** [Tic Tac Toe repo](https://github.com/jthodge/tic-tac-toe)

## R1D9: 2018-06-14

**Today's Progress**: Nothing to commit today as I took ~1 hr to read about  implementing minimax for an AI opponent. Will strive to get this feature functioning tomorrow.
* [Tic Tac Toe: Understanding the Minimax Algorithm](https://www.neverstopbuilding.com/blog/2013/12/13/tic-tac-toe-understanding-the-minimax-algorithm13)
* [How to make your Tic Tac Toe game unbeatable by using the minimax algorithm](https://medium.freecodecamp.org/how-to-make-your-tic-tac-toe-game-unbeatable-by-using-the-minimax-algorithm-9d690bad4b37)
* [How to build an AI that wins: the basics of minimax search](https://blog.vivekpanyam.com/how-to-build-an-ai-that-wins-the-basics-of-minimax-search/)

**Thoughts:** A bit ruffled that I've allowed scope creep to move in and implement an AI opponent instead of shipping...but digging into minimax is going to be so much fun!

**Link to work:** [Tic Tac Toe repo](https://github.com/jthodge/tic-tac-toe)

## R1D10: 2018-06-15

**Today's Progress**: Finally completed all desired features! Perfect minimax AI is good to go. I ended up having to rewrite functions to draw X & O based on boardState index and box size instead of canvas coordinates, because the AI player doesn't trigger 'click' events.

**Thoughts:** A friend pointed out some major flaws in the lack of modern JS practices with this little project, so while I still would like to make those changes and write up a README, it feels absolutely wonderful to ship this.

**Link to work:** [Tic Tac Toe repo](https://github.com/jthodge/tic-tac-toe)
