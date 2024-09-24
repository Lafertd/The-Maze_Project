# The Maze Game

**The Maze** is a 3D maze game that employs ray casting to transform a 2D map into a navigable 3D environment. 
Developed in C using the SDL2 library, the project was built on Ubuntu 24.04 with gcc version 11.3.0.

### About SDL2 

The Simple DirectMedia Layer (SDL) is a cross-platform library that provides low-level access to audio, input, and graphics via OpenGL and Direct3D. It powers video playback, emulators, and many popular games, making it essential for game development.

## Installation 

```sh
$ git clone https://github.com/Lafertd/The-Maze_Project.git
```
## Usage 

* Run the game using `./maze`.
* Use the up and down arrow keys to move forward and backward (the `W` and `S` keys perform the same actions).
* Use the left and right arrow keys to turn the camera (the `A` and `D` keys serve the same purpose).

## Compilation

```sh
gcc -Wall -Werror -Wextra -pedantic *.c -o maze -lm $(sdl2-config --cflags --libs)
```

## Flowchart

[![This-diagram-illustrates-the-flow-of-data-between-different-components-of-the-game.png](https://i.postimg.cc/GhNrprBv/This-diagram-illustrates-the-flow-of-data-between-different-components-of-the-game-including-the-us.png)](https://postimg.cc/56wDPhSt)
## Demo

[![The Maze Demo]( )

## Author :Achraf:

- **Achraf Latrache** <[Usher](https://github.com/Lafertd)>
