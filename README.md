# Asteroids
Arcade asteroids game written in C++, using SDL. 

This project is still in progress and far from ready. I will continue working on it as I have time.

## Prerequisites

 - `cmake` installed on your computer
 - Internet connection:
     - This project uses the SDL2 and SDL_image libraries for graphics and the gtest libraries for testing
     - These libraries are open source
     - It would redundant to include them in this repo so they are included as submodules

## Build

 - Clone this repository with `git clone --recurse-submodules` to also clone the submodules
 - `cd` into the folder
 - Run `cd build`
 - Run `cmake ..` to configure
     - Optionally you can run `cmake -DBUILD_TESTS=1 ..` to include the unit tests also
 - Run `cmake --build .` to build the binaries
 - The executable, called `Asteroids` will be in the _build/bin_ folder, along with the necessary .dll-s

## Controls

 - Right and left arrow keys to rotate the ship
 - Up arrow key to move the ship forward
 - ESC to close the game

## Tests

 - Tested on Windows 10

## Future tasks

- [ ] Start documentation
- [ ] Increase test coverage
- [ ] Handle multiple key presses at the same time
- [ ] Create resizable window
- [ ] Proper Entity Component System
- [ ] Add collision detection
- [ ] Enemy and player objects' better movement
- [ ] Refactor to better match the Model-View-Component pattern and use more modern C++ feature if possible
- [ ] Main menu with settings, like framerate cap or turn music on/off
- [ ] Include audio
- [ ] Animate explosions

