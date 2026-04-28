
# ZIP Game 

# 🧩 LinkedIn Zip Game Clone

A modern, web-ready clone of the popular LinkedIn "Zip" logic puzzle, built entirely in Python! 

This project uses **Flet** to render a beautiful, animated Glassmorphism UI and **NumPy** to handle the underlying Hamiltonian Path grid math.

## ✨ Features
* **Modern UI/UX:** Built with a beautiful deep-purple gradient, floating glassmorphism cards, and glowing neon drop-shadows.
* **Implicit Animations:** Smooth color fading and tile transitions powered by Flet's animation engine.
* **Mathematical Logic:** Uses NumPy to strictly enforce valid Hamiltonian Path moves (no overlapping paths, exact distance checks, and chronological anchor hitting).
* **Cross-Platform & Web Ready:** Can be played as a native desktop app or instantly compiled to WebAssembly (HTML/JS) to be hosted on any static web server.

## 🛠️ Tech Stack
* **Python 3.x**
* **Flet** (UI framework based on Flutter)
* **NumPy** (2D Array tracking and game logic)

## 🎮 How to Play
The goal of Zip is to connect all the numbered anchor points in ascending order (1 ➔ 2 ➔ 3 ➔ 4, etc.) in a single, continuous line. 
1. You must start at the number **1**.
2. You can only move up, down, left, or right.
3. You cannot cross your own path.
4. **Win Condition:** You must visit *every single tile* on the board exactly once, and the final tile you touch must be the final number!
*Tip: If you make a mistake, simply click the "head" of your current path to undo your last move.*

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YourUsername/YourRepositoryName.git](https://github.com/YourUsername/YourRepositoryName.git)
   cd YourRepositoryName

2. **Install the required dependencies:**
   ```bash
   pip install flet numpy

3. **Run the game**


