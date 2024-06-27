# The Maze

The Maze is a 3D maze game created using raycasting and SDL2. The goal of this project is to create a simple but functional 3D game engine that renders a maze environment and allows the player to navigate through it. This project is a part of the Holberton School curriculum.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Maze game utilizes raycasting, a technique used to create a 3D perspective from a 2D map, similar to classic games like Wolfenstein 3D. The game is developed using the SDL2 library, which provides a simple interface for creating windows, rendering graphics, and handling input.

## Features

- Render walls using raycasting.
- Different wall colors based on orientation.
- Rotate the camera using keyboard or mouse input.
- Move the camera within the maze.
- Collision detection to prevent walking through walls.
- Load maze maps from external files.
- Draw a top-down map view.
- Add textures to walls, ground, and ceiling.
- Implement weapons and enemies.
- Add environmental effects like rain.

## Requirements

- Ubuntu 14.04 LTS
- GCC (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4
- SDL2
- SDL2_image

## Installation

To set up the development environment for The Maze, follow these steps:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/your-username/The-Maze.git
    cd The-Maze
    ```

2. **Install SDL2 and SDL2_image:**

    Run the installation script provided:

    ```sh
    ./Install_SDL2.sh
    ```

## Usage

To compile and run the game, follow these steps:

1. **Compile the game:**

    ```sh
    make
    ```

2. **Run the game:**

    ```sh
    ./bin/maze path/to/mapfile
    ```

## Project Structure


