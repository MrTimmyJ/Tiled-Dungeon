# Tiled-Dungeon
Brackeys Game Jam 2025.1: Nothing Can Go Wrong

[Play now on itch.io](https://sourcecodesorcerer.itch.io/tiled-dungeon)

Author: Timothy Johnson <br>
Date: February 16, 2025 to February 23, 2025

Explore a tile-based dungeon with grid-locked movement where each step could bring fortune... or fatal misfortune.
Choose your path wisely — your health and food are limited, and the dungeon is full of surprises.

## Overview

&nbsp;&nbsp;&nbsp;&nbsp;Tiled Dungeon is a top-down 2D dungeon exploration game made for the Brackeys Game Jam.
You move tile by tile through procedurally generated dungeon floors.
Every tile represents a possible outcome — safety, nourishment, nothing at all... or death.
You must survive long enough to reach the end of each floor. With every move, something can go wrong — but will it?

🧩 Features

    🔲 Grid-locked tile-based movement

    💀 Deadly trap tiles, random but lethal

    🍖 Food tiles replenish your energy to keep exploring

    💚 Healing tiles to restore your health

    ⏳ Neutral tiles that waste your time but might hide something

    ⚔️ Rogue-like gameplay with consequences per step

    🔁 Procedurally generated levels (or randomized tile maps)

🎮 Gameplay

Your character (a rogue) moves across a grid-based dungeon. Each tile you step on has a random chance to be:

| Tile Type  | Effect                                   |
| ---------- | ---------------------------------------- |
| 🟩 Healthy | Heals health or restores food            |
| 🟫 Neutral | No benefit or penalty — just wasted time |
| 🟥 Trap    | Harms or kills you instantly             |

Goal: Survive the dungeon and reach the end before your health or food runs out.
Move with care — you won't know the tile type until you step on it!

### Controls:

| Key   | Action     |
| ----- | ---------- |
| ↑ / W | Move Up    |
| ↓ / S | Move Down  |
| ← / A | Turn Left  |
| → / D | Turn Right |
| ESC   | Quit       |

📁 Code Structure

. <br>
├── Main.tscn &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Main scene <br>
├── Player.gd &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Grid movement and input handling <br>
├── DungeonGenerator.gd &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Logic for random tile layout <br>
├── Tile.gd &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Defines tile type and interaction behavior <br>
├── UI.tscn / UI.gd &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Health, food, level, and tile type displays <br>
├── res/ &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Sprites, sounds, and tilesets <br>


⚙️ How It Works

    Player Movement: Uses grid-based logic to snap the player to tiles.

    Dungeon Generation: Tiles are randomly assigned a type each level.

    Tile Interaction: The tile reveals itself and applies an effect upon stepping.

    Health/Food System: Moving consumes food; traps reduce health.
    
🖼️ Screenshots / Visuals

![tileddungeon_banner](https://github.com/user-attachments/assets/a917df8a-7dde-4533-8437-6e1dafae908f)

🧰 Technologies Used

    🕹️ Godot Engine

    🧮 GDScript

    🎨 Custom tiles and sprites

🚀 Getting Started

    To run the game:

    1. Download or clone the repository

        git clone https://github.com/MrTimmyJ/tiled-dungeon.git
        cd tiled-dungeon

    2. Open in Godot Engine

       Launch the Godot editor and open the project folder.

    3. Run the game

       Click "Play Scene" to start the game.

🌱 Planned Features

    🗺️ Fog of war mechanic (hidden tiles)

    ⛏️ Equipment and item pickups

    🐍 Enemy tiles with turn-based combat

    💬 NPC events or lore tiles

    📜 Indication of what the surrounding tiles might be

🪪 License

This open-source project is available under the [MIT License](https://opensource.org/license/mit).

