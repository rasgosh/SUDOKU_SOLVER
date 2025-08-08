# Sudoku Suite — Extended by Kunal Singh

**Base project:** This repository is based on the open-source "Sudoku-Suite" project (original author credited in `ACKNOWLEDGEMENTS`).  
I (Kunal Singh) have extended and improved the project to add new features, tests, and CLI utilities. See the "My contributions" section below for details.

---

## My Contributions
- Added a CLI interface for quick solving and puzzle generation (`cli/`).
- Implemented difficulty levels for puzzle generation (Easy / Medium / Hard).
- Added unit tests and continuous-integration workflow (GitHub Actions).
- Improved performance of solver using heuristics (reduced backtracking on average).
- Created demo scripts and screenshots in `demo/`.

---

## Features
- Solve a Sudoku puzzle from file or command-line input.
- Generate puzzles at three difficulty levels.
- Validate a finished Sudoku grid.
- Reusable `Grid` class for embedding into other projects.

---

## Getting Started (Linux/Windows WSL / Mac)
**Requirements**
- C++17 compiler (g++ >= 7.4 or clang)
- CMake >= 3.11

**Build**
```bash
git clone <your-repo-url>
mkdir build && cd build
cmake ..
make
