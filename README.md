# 💣 Minesweeper Game

<p align="left">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" />
</p>

## 📌 About the Project
This repository contains a modern, mobile-friendly clone of the classic **Minesweeper** puzzle game, built entirely with Flutter. It challenges players to clear a rectangular grid containing hidden "mines" without detonating any of them, using mathematical clues provided by the safe cells.

Building this game in Flutter is an excellent demonstration of handling complex grid states, efficient UI rendering, and reactive state management in a mobile environment.

## ✨ Key Features
* **Dynamic Grid:** A fully responsive grid that adapts to different screen sizes.
* **Reactive Gameplay:** Instant state updates when revealing cells or placing flags.
* **Recursive Revealing (Flood Fill):** Automatically clears adjacent empty cells when a completely safe cell is tapped, providing a smooth gameplay experience.
* **Win/Loss Logic:** Accurately tracks the game state, triggering game over or victory dialogs.
* **Flagging System:** Long-press (or toggle) mechanic to mark suspected mine locations.

---

## 🎮 Gameplay Preview
<img width="270" height="735" alt="image" src="https://github.com/user-attachments/assets/08a651e1-c721-48df-8667-85ff7f855f19" />
<img width="270" height="735" alt="image" src="https://github.com/user-attachments/assets/2e1b3f1e-a819-459f-9b61-7e0ff0653c63" />
<img width="270" height="735" alt="image" src="https://github.com/user-attachments/assets/f62f5090-cecd-46ae-a2a2-10f0824595ab" />

---

## 🛠️ Technologies & Architecture
* **Framework:** [Flutter](https://flutter.dev/)
* **Language:** Dart
* **Core Concepts:** `GridView.builder` for efficient layout mapping, recursive algorithms for the flood-fill effect, and robust state management.

## 🚀 Getting Started

If you want to run this game on your local machine:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/OmerFarukAY/flutter-minesweeper.git](https://github.com/OmerFarukAY/flutter-minesweeper.git)
   cd flutter-minesweeper
2. **Install dependencies:**
   ```bash
   flutter pub get
3. **Run the app:**
   ```bash
   flutter run
(Make sure you have an emulator running or a physical device connected).

---

🕹️ How to Play
Tap a cell to reveal it. If it's a mine, the game is over!

If the cell is safe, it displays a number indicating how many mines are hiding in the adjacent 8 squares.

Use logic to deduce where the mines are. Long-press to place a flag on suspected mines.

You win when all non-mine cells are successfully revealed.

---

Author: Ömer Faruk AY
