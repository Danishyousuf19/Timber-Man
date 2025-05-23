# 🌲 Timber Game (SFML + C++)

This is a simple **Timberman-style arcade game** made with **C++** and **SFML**. Chop the tree as fast as possible while avoiding branches. The game features sound effects, moving backgrounds, and a time-based challenge.


<p align="center">
  <img src="Timber/Output/Timber1.png" alt="Gameplay Screenshot" style="width: 500px; max-width: 100%;" />
</p>

---

## 🎮 Gameplay Features

- Chop tree left or right
- Avoid falling branches
- Countdown timer
- Bee and cloud animations
- Sound effects for chopping, death, and timeout
- Game restart with `Enter` key

---

## 🧪 Controls

| Key       | Action                         |
|-----------|--------------------------------|
| `Enter`   | Start/Restart the game         |
| `Left`    | Chop left                      |
| `Right`   | Chop right                     |
| `Escape`  | Exit game                      |

---

## 🛠 Requirements

- **C++17 or higher**
- **SFML 2.5+** installed

---

## 🚀 How to Compile

**Using g++ (Linux/macOS):**

```bash
g++ main.cpp -o timber -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
./timber
```
###### NOTE This game was developed as a semester project during the Game Development module in our Computer Science syllabus
