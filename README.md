# Follow-the-cursor

An interactive creature simulation built with HTML5 Canvas and JavaScript that responds to your mouse movements.

Inspired by organic motion and limb systems, this animation creates a creature that appears to follow or react to cursor position in real-time.

## 🎯 Features

- 🐾 Limb-based creature animation using segments and angles
- 🖱️ Mouse-tracking for interaction
- 🎨 Canvas-based rendering
- 🦑 Multiple creature types: lizard, tentacle, squid, etc.
- ⚙️ Configurable motion and behavior

## 🧠 How It Works

- Uses **Segment** and **LimbSystem** classes to simulate joints and limbs
- Handles user input (keyboard & mouse) via JavaScript event listeners
- The creature’s movement logic is based on physics-like rules and forward-rotation behavior
- Canvas is updated ~30 times per second using `setInterval`

## 🛠️ How to Run

1. Clone the repository or download the files
2. Make sure you have both `index.html` and `script.js` in the same folder
3. Open `index.html` in your browser  
   OR  
   Use **Live Server** in VS Code for live preview

## 📁 File Structure

CanvasCreatureAnimation/
│
├── index.html # Main HTML file
├── script.js # JavaScript logic for the animation
└── README.md # Project info and instructions

## ✨ Credits

Original logic adapted and inspired by creative coding on Instagram. Modified and explored for educational purpose

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
