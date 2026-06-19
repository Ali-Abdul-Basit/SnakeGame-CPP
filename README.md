# Snake Game in C++ (DSA Lab)

A real-time, console-based implementation of the classic Snake game, developed as part of the Data Structures and Algorithms course.

## 🕹️ Game Overview
The application initializes a rendering grid inside the Windows terminal where the player controls a growing snake. The core objective is to consume food items to increase your score while navigating within tight boundaries.

### Gameplay Rules
- **Movement:** Control the snake's direction using standard keyboard inputs.
- **Growth Engine:** Consuming food increases the snake's length and updates the score metrics.
- **Game Over Conditions:** The game instantly terminates if the snake collides with the boundary walls or intersects with its own growing body.

## 🧱 Key Concepts Implemented
- **Coordinate Tracking:** Uses structured data storage to dynamically manage and shift the sequence of coordinates making up the snake's body.
- **Real-Time Game Loop:** Implements an optimized update pipeline that continuously clears and redraws positions without visual flickering.
- **Collision Detection Algorithms:** Executes rapid positioning checks on every frame tick to evaluate wall boundaries and self-intersection vectors.

## 💻 Environment & Setup
- **Language:** C++
- **IDE Support:** Microsoft Visual Studio
- **Platform:** Windows Console
