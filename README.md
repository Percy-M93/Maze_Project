# The Maze

The Maze is a 3D game that employs ray casting to transform a 2D map into a navigable 3D environment.

The Maze was programmed in C using the SDL2 library. Development took place on Ubuntu 24.04 with gcc (Ubuntu 11.3.0-1ubuntu1~22.04) 11.3.0.

### About SDL2 

Simple DirectMedia Layer (SDL) is a cross-platform development library that offers low-level access to audio, keyboard, mouse, joystick, and graphics hardware through OpenGL and Direct3D. It is utilized by video playback software, emulators, and well-known games, including Valve's award-winning titles and many Humble Bundle games.

## Installation 
```sh
$ git clone https://github.com/Percy-M93/Maze_Project.git
```
## Usage 

- Execute `./maze` or type `make run`
- Use the up and down arrow keys (or the W and S keys) to move forward and backward
- Use the right and left arrow keys (or the D and A keys) to turn the camera around

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Author :black_nib:

- **Percy Mdluli** <[Percy](https://github.com/Percy-M93)>
