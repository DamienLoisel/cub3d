# 🕹️ cub3d

Welcome to **cub3d**, a 3D game project developed at École 42! This project is a graphical application inspired by the classic Wolfenstein 3D, written in C using the [MiniLibX](https://github.com/42Paris/minilibx-linux) library. It features both a mandatory and a bonus version, with extra features and polish in the bonus.

---

## 🚀 Features
- **Raycasting engine**: Real-time 3D rendering from a 2D map
- **Player movement**: WASD controls for smooth navigation
- **Interactive doors**: Open/close doors and interact with special tiles
- **Victory condition**: Find the WINDOWS logo to win!
- **Bonus**: Minimap, animated textures, mouse control, more!

---

## 🛠️ Prérequis
- Linux avec X11
- [MiniLibX](https://github.com/42Paris/minilibx-linux) et ses dépendances :
  - `libxext-dev`, `libx11-dev`, `libbsd-dev`, `libmpg123-dev`, `libpng-dev`, `zlib1g-dev`

## 🛠️ Installation
1. **Clone the repository**
```sh
git clone https://github.com/DamienLoisel/cub3d.git
cd cub3d
```
2. **Build the project**
```sh
make        # For mandatory version
make bonus  # For bonus version
```
3. **Run the game**
```sh
./cub3d <map_file>
./cub3d_bonus <map_file>   # For bonus
```

> **Note:** You need a Linux environment with X11 and the dependencies for MiniLibX (see their README for details).

---

## 🎮 Controls
- `W`, `A`, `S`, `D` : Move the player
- `E` : Open doors / interact
- `←` `→` : Rotate camera
- `Mouse` : Look around (bonus)

---

## 📁 Directory Structure
```
.git/           # Git repository
includes/       # Header files (cub3d.h, cub3d_bonus.h, etc.)
mandatory/      # Main source code for mandatory part
bonus/          # Source code for bonus features
maps/           # Example map files
Makefile        # Build system
```
