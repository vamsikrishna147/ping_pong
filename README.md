# ping_pong
🎮 Pong – Relaxed Edition

A soothing, visually enhanced remake of the classic Pong game — designed for casual, stress-free gameplay.

🧩 Overview

This project is a browser-based Pong game built entirely with HTML5, CSS3, and Vanilla JavaScript — no external libraries required.
The game features modern design themes, smooth animations, power-ups, and an intentionally weaker AI for a relaxing experience.

🚀 Features

Two visual themes:

🟢 Neon Mode – Vibrant glowing visuals

🟤 Retro Mode – Warm wooden tones

Casual gameplay design:

AI with slower reaction and intentional errors

Larger player paddle

Slower ball movement for easy control

Power-ups for players:

🟣 Big Paddle (B) – Expands your paddle size

🟡 Fast Paddle (F) – Boosts movement speed

🟢 Slow AI (S) – Slows down the opponent

Dynamic visual effects:

Neon glow trails

Particle burst effects

Paddle shake feedback

Animated rally counter

🕹️ Controls
Action	Key / Input
Move Paddle Up	↑ Arrow / W
Move Paddle Down	↓ Arrow / S
Mouse / Touch	Drag to move
Pause / Resume	Click Pause button
Reset Game	Click Reset button
🧠 Game Logic Summary

The ball bounces with physics-based angles and spin determined by paddle movement.

AI uses an imperfect prediction system with random delays to make gameplay fair.

Power-ups spawn randomly every 6–12 seconds and only benefit the player.

Game ends when either player reaches the chosen Winning Score (default: 5).

🧰 How to Run

Download or clone the repository.

Open the file index.html directly in your browser.

Click Play — no setup or installation required!

Works seamlessly on both desktop and mobile browsers.

⚙️ Technical Details

Language: HTML, CSS, JavaScript

Rendering: HTML5 <canvas>

Audio: Web Audio API for beep sound effects

Responsive: Auto-resizes based on viewport

Dependencies: None (pure JS)

🌈 File Structure
project-folder/
│
├── index.html        # Main game file (contains HTML, CSS & JS)
└── README.md         # Documentation file

🧪 Customization Tips

Change default theme or difficulty in HTML <select> elements.

Adjust AI strength and paddle sizes in JS variables:

const BASE_PADDLE_H = 140; // player paddle height
const BASE_AI_H = 80;      // AI paddle height


Modify spawnPowerup() timing to control power-up frequency.

🏆 Credits

Developed by [Your Name / Team]
Inspired by the timeless classic Pong with a modern, minimalist twist.

📄 License

This project is open for educational and personal use.
Feel free to modify, remix, or extend — just credit the original source.
