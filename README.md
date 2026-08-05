# 🐍 Snake Battle Fiesta



An action-packed, web-based arcade battle arena where you battle smart AI snakes, consume special power-up fruits, and harvest eliminated competitors to dominate the leaderboard!

---

## 🌟 Key Features

* **🤖 Smart AI Bots**: Battle against multiple computer-controlled snakes (`Viper AI`, `Cyber Cobra`, `Shadow Python`, and `Gold Anaconda`).
* **💥 Body-to-Fruit Explosion**: When a snake crashes into a wall, tail, or another competitor, its entire body disintegrates into eatable fruits for others to scavenge!
* **🍎 Dynamic Power-Up Fruits**:
  * **Red Apple**: Standard point boost and length growth.
  * **Yellow Banana**: Temporary speed boost.
  * **Blueberry**: 2x score multiplier.
  * **Green Grape**: Shrinks your snake's length to improve agility.
  * **Star Fruit**: Magnetizes nearby fruits directly to your snake.
* **🎨 Custom Skins**: Choose your aesthetic before the match begins (Emerald, Cyber, Rainbow, Ruby, Amber, or Violet).
* **📱 Cross-Platform Controls**: Play effortlessly with Keyboard (`WASD` / `Arrow Keys`), Touch Gestures, or the on-screen D-Pad for mobile support.
* **🎵 Web Audio Sound FX**: Retro procedural audio synthesized live via the Web Audio API (no external MP3 downloads required).

---

## 🕹️ How to Play

### Controls
| Control Type | Actions |
| :--- | :--- |
| **Keyboard** | `W`/`Up Arrow` (Up), `S`/`Down Arrow` (Down), `A`/`Left Arrow` (Left), `D`/`Right Arrow` (Right) |
| **Mobile Touch** | Swipe up, down, left, or right on the play area |
| **On-Screen D-Pad** | Tap the directional buttons at the bottom of the screen |

### Rules
1. **Eat Fruits**: Grow your score and snake length while collecting fruit power-ups.
2. **Outmaneuver Competitors**: Force AI snakes to crash into your body or arena walls.
3. **Scavenge Defeated Snakes**: Collect fruit remnants left behind by defeated snakes to rapidly increase your score.
4. **Survive**: Don't hit walls or other snakes' bodies!

---

## 🛠️ Tech Stack

* **Rendering Engine**: Native HTML5 Canvas 2D API
* **Styling**: Tailwind CSS
* **Audio Engine**: Web Audio API (Procedural Synthesizer)
* **Logic**: Vanilla JavaScript (ES6+ Modules & Game Loops)

---

## 🚀 Quick Start / Local Setup

No external node packages or build steps required! Simply clone and open:

```bash
# 1. Clone this repository
git clone [https://github.com/YOUR-USERNAME/snake-battle-fiesta.git](https://github.com/YOUR-USERNAME/snake-battle-fiesta.git)

# 2. Navigate to the folder
cd snake-battle-fiesta

# 3. Open index.html in any modern browser
open index.html
