# 🪁 Kai Po Che! - Uttarayan Simulator
### A High-Fidelity HTML5 Kite Fighting Game set in Khadia, Ahmedabad.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Web](https://img.shields.io/badge/Platform-Web-orange.svg)](https://en.wikipedia.org/wiki/HTML5)

**Kai Po Che!** is a web-based graphical simulator that captures the adrenaline and strategy of the **Uttarayan** festival. Players fly a traditional Indian kite from the terraces of the historic Khadia area in Ahmedabad, engaging in aerial duels to cut the strings of competitors.

---

## 🎮 Gameplay Mechanics

The game features a custom-built physics engine designed to replicate the "Kheench" and "Dheel" dynamics of real-world kite fighting.

### 🧵 The Tension System
* **Kheench (Pull):** Hold the interaction to apply high tension. The kite becomes highly responsive and moves with high velocity—essential for attacking and cutting enemy strings.
* **Dheel (Release):** Release the interaction to let the kite drift. The kite gains lift and floats with the wind. This is used for defensive repositioning and gaining altitude.

### ⚔️ Combat Strategy
* **The Cut:** Success is determined by a combination of velocity, altitude advantage, and the state of your thread. 
* **Thread Management:** You have a finite spindle of *Manjha* (abrasive thread). Excessive pulling consumes your thread; if you run out, you lose the ability to "Pull," making you a sitting duck.

### 🌪️ Environmental Evolution
* **Levels 1-4:** Calm breezes to master steering.
* **Levels 5-10:** Introducing variable wind vectors, gusts, and increased AI aggression.

---

## 🚀 Key Features

* **State-of-the-Art Visuals:** Procedural vector-based graphics ensure the game looks crisp on 4K monitors and mobile screens alike.
* **Realistic Physics:** Incorporates drag, gravity, wind resistance, and string slack simulation.
* **Dynamic HUD:** Track your score, star rating (1-3 based on performance), remaining lives (3 kites per level), and thread percentage.
* **Cross-Platform:** Full touch-control support with a virtual steering zone for mobile devices.
* **Authentic Sound:** Synthesized audio cues for the iconic "cutting" sound.

---

## 🛠️ Technical Stack

* **Engine:** Pure JavaScript (ES6+)
* **Rendering:** HTML5 Canvas API
* **Audio:** Web Audio API (Oscillator synthesis)
* **Styling:** CSS3 Flexbox & Glassmorphism UI

---

## 📖 How to Run

No installation is required. This is a "Zero-Dependency" project.

1.  **Clone this repository:**
    ```bash
    git clone [https://github.com/your-username/kai-po-che-simulator.git](https://github.com/your-username/kai-po-che-simulator.git)
    ```
2.  **Open the file:**
    Simply open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, or Edge).

---

## 🕹️ Controls

| Action | Desktop (Mouse) | Mobile (Touch) |
| :--- | :--- | :--- |
| **Steer** | Move Mouse | Drag on Left Half of Screen |
| **Pull (Kheench)** | Hold Left Click | Hold Right Half of Screen |
| **Release (Dheel)** | Release Click | Release Touch |

---

## 🌟 Scoring & Progression

* **Stars:** Awarded based on your remaining thread and kites at the end of a level.
* **Points:** 100 points per enemy kite cut, multiplied by the level difficulty.
* **Levels:** 10 increasingly difficult stages with varying wind conditions.

---

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.

**Happy Flying! Kai Po Che!**
