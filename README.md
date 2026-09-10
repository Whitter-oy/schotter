# schotter# Schotter

This is my first generative art project for SD5913 Programming for Artists and Designers.

It is inspired by Georg Nees' *Schotter* (1968). The program creates a grid of squares that becomes increasingly disordered from top to bottom.

## How to run

Run the Python file in the terminal:

python3 sketch.py

The program will generate a file called `sketch.svg`.

## Parameters

- `COLS` controls the number of columns.
- `ROWS` controls the number of rows.
- `SEED` changes the random arrangement.
- `CHAOS` controls how quickly the squares become disordered.
- `SQUARE` controls the size of each square.
- `MARGIN` controls the space around the artwork.
- `STROKE` controls the line colour.
- `BACKGROUND` controls the background colour.
- `STROKE_WIDTH` controls the thickness of the lines.

For my second version, I changed `CHAOS` from `1.0` to `1.8` to make the composition become disordered more quickly.