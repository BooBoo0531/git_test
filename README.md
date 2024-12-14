# Snake Multiplayer

A multiplayer version of the classic Snake game developed as part of the NT106.P12_Group17 project.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [License](#license)

---

## Overview

**Snake Multiplayer** is an online multiplayer game where players control a snake that grows longer as it eats food, while competing or cooperating with other players in the same game room. 

This project is built using Unity, featuring custom server-client networking implementation without relying on external network libraries. The game is designed for cross-platform compatibility.

## Features

- Real-time multiplayer gameplay.
- Synchronization between server and clients.
- Room-based gameplay for multiple players.
- Classic snake mechanics with multiplayer twists.
- Simple, lightweight, and fun to play.

## Technologies Used

- **Unity**: Game development framework.
- **C#**: Programming language for game logic and server implementation.
- **Unity Networking**: For built-in network features.
- **Sockets**: Custom network implementation using .NET sockets.

## Setup and Installation

### Prerequisites

- [Unity Hub](https://unity.com/) with **Unity Editor 2022.x** or compatible version.
- [Visual Studio](https://visualstudio.microsoft.com/) with C# development support.

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/BooBoo0531/NT106.P12_Group17.git
   ```

2. Open the project in Unity:
   - Navigate to `D:\Unity\Snake-master\Snake`.
   - Open the project folder using Unity Hub.

3. Open the `Snake` scene in Unity and press **Play** to test locally.

4. For server-client setup:
   - Run the server script (provided in the project folder).
   - Connect multiple clients from Unity to the same server.

5. Build and run the game for standalone use:
   - Go to `File > Build Settings` and select your desired platform.

## How to Play

1. Launch the server application to host a room.
2. Connect multiple game clients to the server.
3. Control your snake to eat food and avoid collisions:
   - Use arrow keys or WASD for movement.
4. Compete or collaborate with other players online!

## Project Structure

```
Snake-master
├── Assets/              # Game assets, scripts, and scenes
├── Server/              # Server-side implementation
├── README.md            # Project documentation
└── ...                  # Other Unity project files
```

## Contributors

This project was developed by **Group 17**, NT106.P12.

- **BooBoo** (Leader): Game logic, server implementation, and documentation.
- [Add other contributors here].

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes!
