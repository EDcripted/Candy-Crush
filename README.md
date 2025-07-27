🍬 ED's Candy Crush
A fun and interactive Candy Crush-style game built using HTML, CSS, and JavaScript. Match candies by dragging them to create combos of 3 in a row to score points!

🎮 Gameplay
Grid: 9x9 board filled with colorful candies.

Drag & Swap: Drag one candy onto an adjacent one to swap.

Match 3: Matching 3 candies vertically or horizontally will clear them.

Gravity: Candies fall down to fill empty spots.

Regeneration: New candies are generated at the top.

Score Tracking: Real-time score updates as you crush candies.

🧠 How It Works
The board is generated dynamically on page load.

Candy elements are <img> tags with drag-and-drop events.

Game loop runs every 100ms to:

Detect and crush 3-candy matches.

Slide candies downward into empty spaces.

Generate new candies at the top.

🗂️ Project Structure
bash
Copy
Edit
project/
│
├── index.html       # Main HTML file
├── candy.css        # Styling (not included in your snippet)
├── candy.js         # Game logic
└── /images/         # Contains images like Blue.png, Red.png, blank.png etc.
📦 Features
Drag-and-drop candy swapping

Valid move detection

Match-3 detection (horizontal & vertical)

Score calculation

Dynamic board updates

🚀 Getting Started
Clone or download the project files.

Make sure you have a folder images/ containing:

Blue.png, Orange.png, Green.png, Yellow.png, Red.png, Purple.png, and blank.png

Open index.html in a browser.

Start playing and match those candies!

<img width="1920" height="948" alt="image" src="https://github.com/user-attachments/assets/439e13fe-f984-42c1-8e04-e34c89c0cd6b" />


📌 Note
The game currently supports only 3-candy matches.

No game-over state or time limits — it's endless fun for now!

The game still has lots of room for improvemnt

