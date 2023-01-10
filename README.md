# The Maze Project - Portfolio

---
![Maze Screenshot](Screenshot%202022-12-26%20140118.jpg)

The maze project is an adaptation of the `Wolfenstein 1981 3D` game. The project uses the concept of Raycasting to serve as the viewpoint of the player, giving it a first-person player view. Maps in the game are created using 2D-matrix arrays, which are seen when the player's raycast touch the blocks of the map.

## Project Execution Outline

- Set up your development environment: Install [**SDL2**](https://wiki.libsdl.org/Installation) and any other dependencies you might need, such as a compiler and build tools [**C Programming Language**](https://linuxconfig.org/how-to-install-gcc-the-c-compiler-on-ubuntu-20-04-lts-focal-fossa-linux). [**Ubuntu 20.04LTS**](https://ubuntu.com/download/desktop) -
The operating system used in this project. Ubuntu is a distro for the Linux Operating system.

- Create the maze: Create the maze as a 2D array, where each element represents a wall or a path. You could also use a vector or some other data structure to store the maze.

- Render the maze: Use SDL2's 2D rendering functions to draw the maze on the screen. You could use a texture for each wall or path tile, or you could draw the maze using basic shapes like lines and rectangles.

- Implement raycasting: Use the raycasting algorithm to determine which walls are visible from the player's perspective. You can then use SDL2 to draw these walls on the screen, giving the illusion of a 3D environment.

- Adding gameplay mechanics: Add features like user input, collision detection, player movement, and picking up items or keys to unlock doors. You could also add enemies or other obstacles to the maze.

- Add sound and music: Use SDL2's audio functions to add sound effects and music to the game.

This is a basic outline of how you could create a maze game using SDL2 and raycasting.

## Usage

Open this folder directory in your Ubuntu (Linux) terminal, then run

```linux
> make
```  

This creates the executable file `raycast` (which is currently in this GitHub repository). Then run this to start up the application.

```linux
./raycast
```

## Reference

- [lazyfoo](http://lazyfoo.net/tutorials/SDL/index.php#Event%20Driven%20Programming)
- [permadi.com](https://permadi.com/1996/05/ray-casting-tutorial-1/)
- [geeksforgeeks](https://www.geeksforgeeks.org/structure-vs-class-in-cpp/)
- [lodev.org](https://lodev.org/cgtutor/raycasting.html)
- [cplusplus.com](https://cplusplus.com/forum/beginner/214311/)
- [pikuma.com](https://pikuma.com/courses/raycasting-engine-tutorial-algorithm-javascript)

## Contributors

- Otitoola Olufolabi [Github](https://github.com/oolufolabii)
- Hanif Miyanji      [Github](https://github.com/hanifanwar380)