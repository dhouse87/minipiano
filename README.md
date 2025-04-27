# 🎹 MiniPiano

Welcome to **MiniPiano** — a fully playable virtual piano built with **Python** and **Pygame**!

This project features:
- 🎵 32 playable keys (C3–G5) mapped to your computer keyboard
- 🎶 Realistic piano sounds loaded dynamically
- 🎨 Light and dark themes toggle
- 🖱️ Mouse control and sustain (hold) modes
- ♾️ Endless free play and dynamic volume adjustment

---

## 🎮 How to Play

- Press the corresponding keyboard keys to play piano notes.
- Click the **SUSTAIN** button to toggle sustain mode (notes continue after releasing keys).
- Click the **MOUSE DOWN** button to enable playing keys with your mouse.
- Adjust volume with the slider.
- Switch between light and dark themes with the **THEME** button.

---

## 📂 Project Structure

```
MiniPiano/
├── Sounds/             # Contains all .wav sound files for each piano key
└── MiniPiano.py        # Main Python game file
```

✅ All assets use **relative paths**, making the project portable across computers and GitHub.

---

## 🛠 Requirements

- Python 3.x
- Pygame library

If you don't have Pygame installed yet, you can install it using:

```bash
pip install pygame
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/dhouse87/minipiano.git
```

2. Navigate into the project folder:

```bash
cd minipiano
```

3. Run the Python file:

```bash
python MiniPiano.py
```

🎶 Enjoy creating your music!

---

## 📢 Credits

- **Sound samples**: Custom-recorded piano sounds
- **Development**: Built by **David Hovsepian**
- **Libraries used**: [Pygame](https://www.pygame.org/)

---

## 🎯 Notes
- Designed for Windows, but should work on Mac/Linux with minor adjustments.
- Sound volume and responsiveness may vary slightly based on your system.
- Optimized for a medium-sized window (roughly 1200x640 pixels).
