# 🧠 Memory Match

A responsive browser-based memory card game built entirely with HTML, CSS, and vanilla JavaScript.

Players flip cards to find matching pairs while managing their attempts and time. Completing levels increases the challenge and rewards players with additional points.

## 🎮 Features

- Interactive card flipping
- Matching pair detection
- Score tracking
- Attempts counter
- Countdown timer
- Multiple difficulty levels
- Level progression
- Time-based scoring
- Game-over screen
- Final score display
- Persistent high score
- Restart functionality
- Keyboard controls
- Responsive card grid
- Card flip animations
- Reduced-motion accessibility support

## 🏆 Difficulty Levels

| Difficulty | Pairs | Cards | Time |
|---|---:|---:|---:|
| Easy | 6 | 12 | 90 seconds |
| Medium | 8 | 16 | 120 seconds |
| Hard | 12 | 24 | 180 seconds |

The game automatically increases the challenge as the player progresses through levels.

## 📊 Scoring

Players earn points for successfully matching pairs.

Additional points are awarded based on remaining time.

Fewer attempts and faster completion can therefore result in higher scores.

## 💾 High Score

The highest score is stored in the browser using:

``javascript
localStorage

This allows the high score to remain available after refreshing the page.

⌨️ Controls
Mouse

Click cards to reveal them.

Keyboard
Key	Action
R	Restart game
Escape	Close game modal
🛠️ Technologies
HTML5
CSS3
JavaScript (ES6+)
CSS Grid
CSS 3D Transforms
DOM Manipulation
Event Listeners
localStorage
📱 Responsive Design

The game adapts to:

Desktop
Laptop
Tablet
Mobile devices

The card grid automatically adjusts according to screen size and difficulty.

🎯 Project Goals

This project demonstrates practical JavaScript concepts including:

Application state management
Arrays
Objects
DOM manipulation
Event handling
Timers
Randomization
Array shuffling
Conditional logic
localStorage
Dynamic rendering
Responsive design

📂 Project Structure
memory-match-game/
│
├── index.html
│
├── css/
│   └── style.css
│
├── js/
│   └── game.js
│
└── README.md
