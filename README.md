# Flappy Bird Game

This is a Flappy Bird game developed using Visual Studio 2022 and SFML library. The game is a clone of the popular mobile game "Flappy Bird," where the player controls a bird and tries to navigate it through a series of pipes without touching them.

## Prerequisites

Before running the game, make sure you have the following prerequisites installed on your system:

- Visual Studio 2022: [Download Visual Studio 2022](https://visualstudio.microsoft.com/downloads/)
- SFML library: [Download SFML](https://www.sfml-dev.org/download.php)

## Getting Started

To get started with the game, follow these steps:

1. Clone the repository to your local machine using the following command:
git clone https://github.com/your-username/flappy-bird-game.git
2. Open the project in Visual Studio 2022.

3. Configure SFML library in Visual Studio:
- Right-click on the project in Solution Explorer and select "Properties."
- Navigate to "C/C++" -> "General" -> "Additional Include Directories" and add the path to the SFML header files.
- Navigate to "Linker" -> "General" -> "Additional Library Directories" and add the path to the SFML libraries.
- Navigate to "Linker" -> "Input" -> "Additional Dependencies" and add the SFML library names (e.g., sfml-graphics.lib, sfml-window.lib, sfml-system.lib).

4. Build the project to ensure that all dependencies are resolved.

5. Copy the required SFML DLL files (e.g., sfml-graphics-2.dll, sfml-window-2.dll, sfml-system-2.dll) to the output directory (where the executable is generated). You can find these DLL files in the SFML library installation directory.

6. Run the game by clicking the "Start" button in Visual Studio or by launching the generated executable directly.

7. Enjoy playing Flappy Bird!

## Controls

Press the spacebar or left mouse button to make the bird flap and avoid the pipes.

## Contributing

Contributions to the project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

