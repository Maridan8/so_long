# So_long
so_long is the first graphical project of the 42 common core. The goal was to reproduce a small 2d arcade game with all the basic functionalities (window creation, sprite movement, collisions, ...).
Minilibx was used to write the project

## Game's rules:
  
    • The player’s goal is to collect every collectible present on the map, then escape chosing the shortest possible route.
    • The W, A, S, and D keys must be used to move the main character.
    • The player should be able to move in these 4 directions: up, down, left, right.
    • The player should not be able to move into walls.
    • Pressing ESC must close the window and quit the program in a clean way.
    • Clicking on the cross on the window’s frame must close the window and quit the program in a clean way.
    • The player should lose when they touch an enemy patrol.

## Installing and running the project:

1- Clone the repo:

    git clone https://github.com/startaglia/so_long.git so_long

2- Enter in so_long dir then enter in minilibx dir and compile the lib with `make re` command
	
     cd so_long/minilibx_2 && make re

3- Return back on so_long dir and compile with `make re` command

    cd .. && make re
    
4- Now you could launch the game! Try it with different maps (you can choose between map_0.ber, map_1.ber, map_2.ber, map_3.ber map_4.ber) 

    ./so_long assets/maps/map_0.ber
 
### Makefile Available Targets:

`make` or `make all` - Makes exe file/s</br>
`make clean` - Deletes all the resulting object files  
`make fclean` - Deletes the executables and all the resulting object files  
`make re` - fclean + all
</br></br>

## Technologies Used:

- **Programming Language**: C
- **Operating System**: Linux
- **Compiler**: GCC (GNU Compiler Collection)
- **Build System**: GNU Make
- **C Standard Library**
- **Graphics Library**: MinilibX (a lightweight graphics library for window and image management)
- **Input Handling**: Techniques for handling keyboard input using MinilibX
- **Time Measurement**: Techniques for measuring time using `sys/time.h`
- **Command Line Arguments Handling**: Techniques such as `argc/argv` for parsing command line arguments

## Authors:

- **Simone Tartaglia**
  - Email: [startaglia89@gmail.com](mailto:startaglia89@gmail.com)
  - GitHub: [startaglia](https://github.com/startaglia)
  - LinkedIn: [Simone Tartaglia](https://www.linkedin.com/in/simone-tartaglia-134723248/)

- **Simone Castagnoli**
  - GitHub: [IamG-Root](https://github.com/IamG-Root)

- **Davide Carassiti**
  - GitHub: [DarkB0shy](https://github.com/DarkB0shy)
