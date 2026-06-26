# Backroom: One Minute to Escape

A short psychological horror game developed in **Python** using **Pygame** for a Game Jam.

## About

You wake up in the mysterious Backrooms with no memory of how you got there.

To escape, you must complete each level before the timer reaches zero.

Every level introduces a new objective while the atmosphere becomes increasingly oppressive.

The final level turns into a desperate escape where survival is your only goal.

---

## Features

* Pseudo-3D raycasting engine
* 5 unique levels
* One-minute challenge per level
* Atmospheric sound design
* Dynamic lighting and textured walls
* Horror events and jumpscares
* Final chase sequence
* Main menu with options
* Optimized for Windows and Linux

---

## Controls

| Key             | Action      |
| --------------- | ----------- |
| **ZQSD / WASD** | Move        |
| **Mouse**       | Look around |
| **Shift**       | Sprint      |
| **E**           | Interact    |
| **ESC**         | Pause       |

---

## Technologies

* Python
* Pygame CE
* NumPy
* PyInstaller

---

## Project Structure

```text
assets/
├── audio/
├── fonts/
├── images/
└── textures/

config.py
DOCUMENTATION.md
game.py
main.py
render.py
requirements/txt
settings.py
sounds.py
state.py
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/ODG747/Backroom-One-Minute-to-Escape.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the game:

```bash
python main.py
```

---

## Build

### Windows

```bash
pyinstaller --onefile --windowed --add-data "assets;assets" main.py
```

### Linux

```bash
pyinstaller --onefile --windowed --add-data "assets:assets" main.py
```

---

## Screenshots

Add screenshots of the game here.

---

## Authors

Developed during a Game Jam by Studio Mossard

---

## License

This project was created for educational purposes and a Game Jam.

Feel free to explore the code and learn from it.
