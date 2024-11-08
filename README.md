# Endless Car Racer

**Endless Car Racer** is a fast-paced driving game built with the [raylib](https://www.raylib.com/) library. Navigate through traffic, avoid collisions, and score points. The game offers simple controls and exciting gameplay.

## Features

- **Random Vehicles**: Vehicles spawn randomly across lanes, increasing the challenge as the game progresses.
- **Score Tracking**: Your score increases as you avoid vehicles and survive longer, with your highest score saved.
- **Responsive Controls**: Use the arrow keys to move your car left or right to avoid other vehicles.
- **Game Over Screen**: After a crash, view your score and high score, with options to restart or exit.

## Installation

### Prerequisites

- **raylib**: You need to have raylib installed on your system. Follow the installation guide for raylib based on your platform: [raylib installation](https://www.raylib.com/).
- **C++ Compiler**: Ensure you have a C++ compiler like GCC or Clang.

### Installing raylib

Follow the installation guide for your platform at [raylib installation guide](https://www.raylib.com/).

### Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/alintm4/Endless-Car-Racer-Cpp.git
cd endless-car-racer
```
## Build the Game

After cloning, compile the game using:

```bash
g++ -o endless-car-racer main.cpp -lraylib -lm -lpthread -ldl -lrt -lX11
```
## Running the Game

To start the game, run:

```bash
./endless-car-racer
```
## How to Play

- **Start the Game**: Choose from the menu options to start the game, view instructions, or check your high score.
- **Control the Car**: Use the left and right arrow keys to move your car between three lanes.
- **Avoid Collisions**: Dodge the randomly spawning vehicles. If you collide with one, the game ends.
- **Score**: Earn points by successfully avoiding vehicles. The speed of the game increases as your score grows.
- **Game Over**: After a collision, your score will be displayed. Press Y to restart or N to exit.
- **High Score**: Your highest score is saved and displayed in the High Score menu.
## Key Controls

- **Arrow Keys**: Move left or right between lanes.
- **Backspace**: Return to the main menu.
- **Y**: Restart after a game over.
- **N**: Exit the game.
## Contributing

Feel free to fork the repository, make changes, and submit a pull request. Please ensure proper code formatting and add comments where necessary.
## License

This project is licensed under the MIT License. You can view or download the full license from the [LICENSE file](license.txt).
