# 🪁 Kai Po Che: Legend of the Skies
### A High-Fidelity HTML5 Kite Fighting Simulator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform: Web](https://img.shields.io/badge/Platform-Web-orange.svg)](https://en.wikipedia.org/wiki/HTML5)
[![Status: Release Candidate](https://img.shields.io/badge/Status-Release_Candidate-green.svg)]()

**Kai Po Che!** is a web-based graphical simulator that captures the adrenaline and strategy of the **Uttarayan** festival. Players fly a traditional Indian kite from the terraces of the historic Khadia area in Ahmedabad, engaging in aerial duels to cut the strings of competitors.

> **🤖 Development Credits:**  
> This project was **Planned and Coded in Claude** and subsequently **Refined and Polished in Gemini**.

---

## 🕹️ How to Play & Controls

The goal is to defeat enemy kites by cutting their strings while maintaining your own thread tension and health.

### 🎮 Controls

| Platform | Action | Input |
| :--- | :--- | :--- |
| **Desktop** | **Steer** | Move Mouse Left / Right |
| | **Pull (Attack)** | Hold **Left Click**, **Spacebar**, or **Arrow Up** |
| | **Release (Defend)** | Release Click/Key |
| **Mobile** | **Steer** | Slide Finger Left / Right |
| | **Pull (Attack)** | Touch & Hold Screen |
| | **Release (Defend)** | Lift Finger |

### ⚔️ Combat Basics
1.  **Engage:** Steer your kite towards an enemy. When strings cross, **War Mode** begins.
2.  **The Cut:** Rapidly **PULL** (hold input) when you have the advantage to cut the enemy's string.
3.  **Tension:** If your thread meter runs out, you lose tension and cannot attack. Release to recharge.
4.  **Radar:** Use the HUD Radar to spot enemies. Enemies inside the **white box** are visible on your screen.

---

## 🚀 Key Features

### 🎵 Procedural Audio Engine
*   **Dynamic Soundtrack:** Features a custom Web Audio API engine that generates **Happy Indian Folk Music** (Sitar & Tabla) in real-time.
*   **Adaptive Audio:** The music automatically shifts to intense **Battle Drums** when you engage in combat and returns to a melody when the skies are clear.

### 🧠 Advanced AI & Physics
*   **Smart Spawning:** Enemies utilize a "Safe Spawn" system to ensure they don't cluster or spawn on top of the player.
*   **Separation Logic:** AI kites will naturally drift apart if they get too close to one another, preventing unfair "gang-up" scenarios.
*   **Disengagement:** Combat utilizes **Euclidean distance checks**, meaning fights will naturally break off if kites fly too far apart in any direction (vertical or horizontal).

### 🖥️ Visuals & UI
*   **High-Fidelity Graphics:** Procedural vector-based rendering with high-poly kite models and dynamic tails.
*   **Smart Radar:** A 360-degree radar with a "Field of View" box to help you locate off-screen threats.
*   **Dynamic Camera:** The camera smoothly pans and zooms during combat to frame both you and your opponent.
*   **HUD Stats:** Track your **Score**, **Lives**, **Thread Tension**, and total **Kites Cut**.

---

## 🎮 Gameplay Mechanics

The game features a custom-built physics engine designed to replicate the *"Kheench"* and *"Dheel"* dynamics of real-world kite fighting.

### 🧵 The Tension System
*   **Kheench (Pull):** Hold input to apply high tension. The kite becomes highly responsive and moves with high velocity—essential for attacking.
*   **Dheel (Release):** Release input to let the kite drift. The kite gains lift and floats with the wind. Use this to regenerate your thread meter.

### 🌪️ Environmental Evolution
*   **Levels 1-4:** Calm breezes to master steering.
*   **Levels 5-10:** Introducing variable wind vectors, gusts, and increased AI aggression.

---

## 🛠️ Technical Stack

*   **Engine:** Pure JavaScript (ES6+) - Zero Dependencies
*   **Rendering:** HTML5 Canvas API (2D Context)
*   **Audio:** Native Web Audio API (Oscillator Synthesis for music & SFX)
*   **Styling:** CSS3 Flexbox, Glassmorphism, & CSS Animations

---

## 📖 Installation

No installation is required. This is a standalone HTML5 game.

1.  **Clone this repository:**
    ```bash
    git clone https://github.com/your-username/kai-po-che-simulator.git
    ```
2.  **Run:**
    Simply open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, or Edge).

---

## 🌟 Scoring & Progression

*   **Stars:** Awarded based on your remaining thread and kites at the end of a level.
*   **Kites Cut:** A persistent counter tracks your total kills across the session.
*   **Points:** Earn 100 base points per cut, with multipliers for difficulty and speed.

---

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.

**Happy Flying! Kai Po Che!**
