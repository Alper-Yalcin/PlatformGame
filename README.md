# 🕹️ 2D Platformer Game (Unreal Engine 5)

This is a 2D platformer game developed using **Unreal Engine 5**, featuring classic mechanics like jumping, dashing, enemy interactions, and platforming challenges. The project utilizes both **Paper2D** and **PaperZD** for advanced sprite and animation control.

## 🎮 Gameplay Features

- **Move Left and Right**  
  The player can move horizontally using keyboard input.

- **Jumping**  
  Basic jump mechanic for navigating between platforms.

- **Directional Dash**  
  Players can perform a fast dash in any direction to reach new areas or evade hazards.

- **Defeat Enemies by Jumping**  
  Jump on enemies to defeat them, inspired by traditional platformer games.

- **Lose on Enemy or Trap Collision**  
  Touching enemies (from sides or below) or traps (like spikes) causes the player to be eliminated.

## 🌍 Level & Platform Design

- **TileMap-Based Level Design**  
  Maps are built using Unreal Engine's TileMap system, allowing flexible and modular 2D level creation.

- **One-Sided and Two-Sided Platforms**  
  - *One-sided platforms*: Player can jump through them from below and land on top.  
  - *Two-sided platforms*: Solid from all directions.

## 🧰 Technologies Used

- **Unreal Engine 5**
- **Paper2D** – for 2D sprites and TileMaps  
- **PaperZD** – for advanced animation management (state machines, transitions)  
- **Blueprint Visual Scripting** – no C++ required  
- **Flipbook Animations** – powered by PaperZD for smooth transitions

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/2D-Platformer-UE5.git
