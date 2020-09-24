# Amnesia: The Dark Descent Source Code - HPL Chad Gang Fork

This is a fork of the Amnesia the Dark Descent repository from FrictionalGames. We will mostly play with different parts of the engine and perhaps even fix some bugs :)

## Project Overview
The game is built from two separate solutions: The HPL2 Engine and the game itself.

## Prerequisites

- A copy of Amnesia: the Dark Descent (For playing the game)
- Visual Studio 2010 (For compiling the engine, 2010 solution)
- Visual Studio 2017 (For compiling the game - newer versions may work as well)
- CMake

## Project Overview
The game is built from two separate solutions: The engine solution named `HPL2_2010` and the main game solution named `Lux`.
The project also includes all the different editors and additional tools, such as the Level Editor and the Model Editor.

### Engine Overview
Todo: Add some descriptions about what kind of files we have in the engine solution.

### Game Overview
Todo: Add some descriptions about what kind of files we have in the game solution.

## Building & Playing (Windows)
In order to build the game on Windows, you will first need to compile and build the HPL2 Engine.

### Building the Engine 
1. Clone the project
2. Go to the `HPL2/` folder and extract `dependencies.zip`.
3. Open `_HPL2_2010.sln` with Visual Studio 2010.
4. Set the build configuration from `Debug` to `Release`.
5. `Build -> Build _HPL2_2010`. There won't be any errors, but some warning messages will appear.
6. The build result will be created in `HPL2/lib`

### Building the Game
1. Go to `amnesia/src/game` and open `Lux.sln`.
2. Click cancel on retag project message.
3. Set the build configuration from `Debug` to `Release`.
4. `Build -> Build Lux`.  There won't be any errors, but some warning messages will appear.
5. The game executable should be created in `amnesia/redist`.

### Playing the Game
Copy `Amnesia.exe` into your Amnesia game folder and launch it. The main menu should appear normally with no errors.

### Building the Editors

## Building & Playing (Mac)

### Building the Engine 

### Building the Game

### Playing the Game

### Building the Editors

## Building & Playing (Linux)

### Building the Engine 

### Building the Game

### Playing the Game

### Building the Editors

## License Information
All code is under the GPL Version 3 license. Read the LICENSE file for terms of use of the license.