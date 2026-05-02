# 🐍 Snake Game - C++ Console Edition

A feature-packed Snake game built in C++ for Windows console, featuring **multiple levels**, **custom wall designs**, **progressive difficulty**, and smooth console rendering.


## 🎮 Game Features

- **4 Unique Level Maps** - Each level has different wall layouts and maze patterns
- **3 Difficulty Modes** - Easy (slow), Medium (normal), Hard (fast)
- **Wall Collision System** - Walls block movement; some levels have complex maze designs
- **Wrapping Boundaries** - Snake wraps around screen edges (configurable per level)
- **Self-Collision Detection** - Game ends if snake hits its own tail
- **Dynamic Speed Increase** - Game speeds up slightly each time food is eaten
- **Score & Length Tracking** - Real-time display of score and snake length

## 📋 Level Previews

| Level | Wall Pattern |
|-------|--------------|
| **Level 1** | Border walls with 4 gate openings (top/bottom at columns 5-8 & 12-15) |
| **Level 2** | Borders + 3x3 block obstacles scattered in a grid pattern |
| **Level 3** | Complex maze with corridors, diagonal barriers, and restricted zones |
| **Level 4** | Cross-shaped obstacles + border walls with gaps |

## 🕹️ How to Play

### Controls
- **W / ↑** - Move Up
- **S / ↓** - Move Down  
- **A / ←** - Move Left
- **D / →** - Move Right
- **ESC** - Exit game

### Game Rules
1. Eat the food `F` to grow longer and increase score (+10 points)
2. Avoid hitting walls `#` (varies by level)
3. Don't collide with your own body `O`
4. Each level introduces new wall patterns and challenges
5. Game gradually speeds up as you eat more food

## 🚀 Getting Started

### Prerequisites
- Windows OS (uses `windows.h` and `conio.h`)
- C++ compiler (MinGW, Visual Studio, or any C++17 compatible compiler)
