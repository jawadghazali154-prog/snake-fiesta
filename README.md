Snake Battle Fiesta

A fast-paced, action-packed retro-arcade battle arena built using HTML5 Canvas, Tailwind CSS, and pure JavaScript. Battle against AI-controlled snakes, grab fruit power-ups, and feast on the remains of your defeated opponents!

🌟 Key Features

🤖 AI Bot Opponents: Battle up to 3 computer-controlled snakes navigating the grid in real time.

💥 Body-to-Fruit Explosion: Defeated snakes disintegrate into a cluster of eatable fruits for high-stakes looting!

🎨 Skin Customization: Choose from 6 custom snake skins before entering the match:

🟢 Emerald

🌐 Cyber

🌈 Rainbow

🔴 Ruby

🟡 Amber

🟣 Violet

🍎 Dynamic Fruits & Power-Ups:

🍎 Apple: Standard points (+10)

🍌 Banana: Temporary Speed Boost (+20)

🫐 Blueberry: 2x Score Multiplier (+25)

🍇 Grape: Shrinks Snake Length (+35)

⭐ Star: Fruit Magnet effect (+50)

🏆 Live Arena Leaderboard: Tracks live scores, player ranks, and active/eliminated statuses.

🔊 Synthesized Audio: Built-in Web Audio API synthesizer for sound effects (eating, power-ups, game over) with no external audio file dependencies.

🕹️ Cross-Platform Controls: Full support for Keyboard (WASD / Arrows), Mobile Touch Swipes, and an On-Screen D-Pad.

⚙️ Customizable Match Rules: Toggle solid wall collisions vs. pass-through borders, plus game speed settings (Chill, Normal, Turbo).

🕹️ How to Play

Controls

Input Method

Action

W / Up Arrow

Move Up

S / Down Arrow

Move Down

A / Left Arrow

Move Left

D / Right Arrow

Move Right

P

Pause / Resume

Touch Swipe

Swipe direction on canvas (Mobile)

D-Pad

On-screen directional buttons (Mobile)

Game Rules

Eat fruits scattered around the arena to grow your snake and earn points.

Avoid running into walls (unless Pass-Through is enabled) or other snakes' bodies.

Outmaneuver AI bots—force them to crash into your body to turn them into valuable fruits!

Collect star power-ups to activate the magnet effect and pull nearby fruits toward your snake head.

🚀 Quick Start & Deployment

Run Locally

Since the entire game is built into a single self-contained HTML file, running it locally is effortless:

Clone or download this repository:

git clone https://github.com/your-username/snake-battle-fiesta.git


Navigate into the repository folder.

Open index.html in any modern web browser (Chrome, Firefox, Safari, Edge).

Deploy to GitHub Pages

To publish and share your game live online for free:

Push this repository to GitHub.

Go to Settings > Pages in your GitHub repository menu.

Under Build and deployment, select main branch and / (root) folder.

Click Save. Your game will be live at https://your-username.github.io/snake-battle-fiesta/ within minutes!

🛠️ Tech Stack

HTML5 Canvas: 2D rendering engine for smooth grid drawing, animations, and particle effects.

Tailwind CSS (CDN): Modern utility-first CSS styling for UI overlays, glassmorphism cards, and responsive controls.

Vanilla JavaScript (ES6+): Complete game loop physics, AI decision-making algorithms, collision detection, and dynamic state management.

Web Audio API: Synthesizes sound frequencies dynamically on user interaction without requiring external .wav or .mp3 assets.

FontAwesome & Google Fonts: Clean iconography and typography ('Fredoka' & 'Outfit').
