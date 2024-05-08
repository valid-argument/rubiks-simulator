# Rubiks-simulator
2D simulator for Rubik's Cube. A project in Python.

**Requirements**
* Python 3.12.2
* Numpy 1.26.4
* Sympy 1.12
* Matplotlib 3.8.3
* Jupyter Notebook

**Features**
* Create instances of Rubik's Cube with arbitrary states
* Control the cube via text commands using the conventional Rubik's Cube Notation
* Run arbitrary algorithms
* 2D visualization
* Solver based on CFOP method

How to use?
-----------
The app is super-easy to use and you can find some self-explanatory examples in the notebook to get you started. There are just a few things you need to know before, first of all, the conventional [Rubik's Cube Notation](https://ruwix.com/the-rubiks-cube/notation/). Note that the app can handle clockwise [U, L, F, R, B, D, M, E, S], counterclockwise [U', L', F', R', B', D', M', E', S'] and double [U2, L2, F2, R2, B2, D2, M2, E2, S2] turns of all faces and slices, as well as whole cube rotations [X, Y, Z, X', Y', Z', X2, Y2, Z2], but no other notation.

The following figure helps you to identify faces in the 2D representation of the cube.

```
+---+---+---+---+---+---+---+---+---+---+---+---+
|           |   |   |   |                       |
+           +---+---+---+                       +
|           |   | U |   |                       |
+           +---+---+---+                       +
|           |   |   |   |                       |
+---+---+---+---+---+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+
|   | L |   |   | F |   |   | R |   |   | B |   |
+---+---+---+---+---+---+---+---+---+---+---+---+
|   |   |   |   |   |   |   |   |   |   |   |   |
+---+---+---+---+---+---+---+---+---+---+---+---+
|           |   |   |   |                       |
+           +---+---+---+                       +
|           |   | D |   |                       |
+           +---+---+---+                       +
|           |   |   |   |                       |
+---+---+---+---+---+---+---+---+---+---+---+---+
```

And the next figure shows the position of each piece, which you will need to define an arbitrary state of the cube.

```
+---+---+---+---+---+---+---+---+---+---+---+---+
|           | 0 | 1 | 2 |                       |
+           +---+---+---+                       +
|           | 3 | 4 | 5 |                       |
+           +---+---+---+                       +
|           | 6 | 7 | 8 |                       |
+---+---+---+---+---+---+---+---+---+---+---+---+
| 9 | 10| 11| 18| 19| 20| 27| 28| 29| 36| 37| 38|
+---+---+---+---+---+---+---+---+---+---+---+---+
| 12| 13| 14| 21| 22| 23| 30| 31| 32| 39| 40| 41|
+---+---+---+---+---+---+---+---+---+---+---+---+
| 15| 16| 17| 24| 25| 26| 33| 34| 35| 42| 43| 44|
+---+---+---+---+---+---+---+---+---+---+---+---+
|           | 45| 46| 47|                       |
+           +---+---+---+                       +
|           | 48| 49| 50|                       |
+           +---+---+---+                       +
|           | 51| 52| 53|                       |
+---+---+---+---+---+---+---+---+---+---+---+---+
```

And that's all! Have fun! 🎉


