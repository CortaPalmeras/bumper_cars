# Project Overview

This project consists of simple 3D action game with a top-down perspective. The player controls a bumper car with the objective of kicking the enemy car out of the playing field.

## Game Mechanics

### Player Controls

- **Acceleration**: Hold down the left mouse click to propel your car in the direction of the mouse pointer.
- **Dash Attack**: Execute a swift dash attack towards the mouse pointer by pressing the right mouse click.
- **Throwable Object**: Throw a bouncy box toward your mouse cursor by pressing on the 'R' key.

### Collision Interactions

The bouncy squares can interact with each other and with the bumper cars, creating dynamic and unpredictable moments in the game.

## Dependencies and Execution

This application relies on four Python libraries: Pyglet, PyOpenGL, NumPy and Pillow. To install these dependencies, use pip:

```bash
pip install pyglet pyopengl numpy pillow
```

Once the dependencies are installed, the program can be executed by running the following command in the terminal:

```bash
python cars.py
```