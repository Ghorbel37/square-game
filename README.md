# Carreau (square game)

A 2D mobile-friendly prototype. One piece lives in a square board and changes shape every time it moves.

- Left / right changes the width: small on the left, big on the right.
- Up / down changes the height: small at the bottom, big at the top.

So the four corners give four shapes: small square (bottom-left), tall rectangle (top-left), big square (top-right), wide rectangle (bottom-right). Moving toward a wall you already touch does nothing (the piece bumps).

**Play 30 s**: match the dashed target shape as many times as you can. Reaching it in the fewest moves builds a combo.
**Free play**: just move and watch it morph.

Controls: swipe, arrow keys / WASD, or the on-screen pad.

## Run

Open `index.html` in any browser, phone included. No build step.

`src/game.html` is the game body; `index.html` is the same content wrapped in a full HTML document.
