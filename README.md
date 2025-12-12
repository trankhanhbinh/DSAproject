## 👥 Team
| No. | Student name | Student ID | Contribution |
|-----|--------------|------------:|-------------:|
| 1 | Nguyễn Việt Thảo | ITCSIU23058 | 25% |
| 2 | Huỳnh Khắc Tấn Minh | ITITWE23038 | 25% |
| 3 | Trần Khánh Bình | ITCSIU24015 | 25% |
| 4 | Phan Minh Khánh | ITITWE23020 | 25% |

---

## 📘 Short description
This is a simple Pacman implementation built for educational purposes (Algorithms & Data Structures). The game runs in the browser and demonstrates basic data structures and simple AI behaviors for ghosts.

## ✨ Key features
This project focuses on several core game systems implemented with clarity and educational purpose:

1. Maze Initialization
   - Map/maze loading and grid initialization: walls, pellets, and power pellets are loaded and rendered on the grid; supports different map files.
2. Pacman Movement
   - Smooth Pacman movement and player input handling (arrow keys); tile-based movement, collision detection with walls and collectibles, and responsive turning near corners.
3. Ghost AI (Namco Algorithm)
   - Ghost behaviors implement the original Namco algorithms (Blinky, Pinky, Inky, Clyde), including scatter/chase modes and target calculation strategies for authentic ghost movement.
4. State Machine
   - Finite state machine used for Pacman/ghost state transitions—modes such as scatter, chase, frightened, and respawn states.
5. Game Loop
   - Main game loop with a fixed update/draw cycle, handling inputs, updates, collision checks, and rendering at a stable rate.
6. Scoring System
   - Pellet and power pellet scoring, scoring for eating ghosts (when powered), high-score tracking, and basic HUD display.

## ✅ Testing & contributions
- Open an issue if you find a bug or would like a new feature.  
- Send a pull request with a clear description of changes and instructions on how to test them.

## 📁 Files
- `index.html` — main page to launch the game
- `style.css` — user interface styles
- `assets/` — images, sounds and other resources
- `js/` — main JavaScript source files:
   - `Game.js` — core game engine and main loop
   - `Map/Map.js` — map loading & rendering
   - `Pacman.js` — player controller
   - `Ghosts/GhostAI.js` and `Ghosts/Ghosts.js` — ghost AI and behavior systems
   - `GhostTimer.js`, `Global.js`, `GridUtils.js` — utility and timing modules

## 📜 License
This project is for educational purposes. If you'd like to reuse it for other purposes, please contact the authors.

## 🎮 Project Overview
The game features:
- A controllable Pacman navigating through a maze.
- Four ghosts with different behaviors.
- Collision detection, score tracking, and win/lose conditions.
- Lightweight console-based graphics using characters.

## 🛠️ Key Technologies
- **OOP design**
- **File handling** for map loading
- **Data structures**: arrays, vectors
- **Algorithms**: pathfinding logic, movement patterns
