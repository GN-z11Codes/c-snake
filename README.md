# Snake Game
A simple Snake game written in C language that can be run on the terminal. The game involves controlling a snake to move around the game board and eat apples to grow in length. The game ends when the snake collides with itself or the boundaries of the game board.

## Getting Started
These instructions will get you a copy of the Snake Game up and running on your local machine.

### Prerequisites
To run the Snake Game, you need to have the following installed:
- A C compiler (GCC or Clang)
- Terminal emulator

### Installing
Follow the instructions below to install the Snake Game:
1. Clone the repository using the command below:
```
git clone https://github.com/GN-z11Codes/snake-game.git
```
2. Change the directory to the cloned repository:
```
cd snake-game
```
3. Compile the code using GCC:
```
gcc -o snake snake.c
```
4. Run the game:
```
./snake
```

## How to Play
- Use the following keys to control the movement of the snake:
  - `h` - Move left
  - `j` - Move down
  - `k` - Move up
  - `l` - Move right
- Eat the apples to grow the length of the snake
- The game ends when the snake collides with itself or the boundaries of the game board.

## Authors
- GN-z11Codes

## Version History
- 1.0 (2023-05-15)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Ncurses library](https://invisible-island.net/ncurses/) for the game board design and control
- [Termios library](https://linux.die.net/man/3/termios) for the terminal input control.
