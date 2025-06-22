# <i>**`Simon`** Memory Game</i>

A classic **`memory challenge game`** built with modern web technologies for testing and improving memory skills through sequential pattern recognition.

<samp>

## 🌐 Live Demo

**Play Now**: [**Simon Game**](https://max-eee.github.io/Simon-Game/) <br>
Experience the classic memory game directly in your browser without any installation required.
  
> [!IMPORTANT]
> **How to Win**: Successfully repeat increasingly longer color sequences to achieve the highest score possible.
> 
> **Memory Challenge**: This game progressively increases difficulty with each successful round, testing your memory limits.

## 🎴 Design
![Screenshot 2025-06-22 171111](https://github.com/user-attachments/assets/f656fe44-2e29-4865-bddf-e6ca5313ae45)
![Screenshot 2025-06-22 171131](https://github.com/user-attachments/assets/5142d0e2-0359-4b1b-8202-cc7f497b0e2e)

## 🎮 Game Rules

The Simon Game follows the classic memory game rules:

1. **Sequence Display**: The game shows a sequence of colored buttons lighting up
2. **Player Input**: You must repeat the sequence by clicking buttons in the same order
3. **Progressive Challenge**: Each successful round adds one more step to the sequence
4. **Memory Test**: Continue until you make a mistake or achieve your personal best
5. **Score System**: Your score equals the number of sequences successfully completed
## ✨ Features

- **`Interactive Game Board`** : Four colored buttons with responsive click detection and visual feedback
- **`Progressive Difficulty`** : Sequences grow longer with each successful round for increasing challenge
- **`Audiovisual Feedback`** : Sound effects and visual cues enhance the gaming experience
- **`Score Tracking System`** : Real-time current score display with persistent high score records
- **`Game State Management`** : Seamless transitions between game start, playing, and game over states
- **`Responsive Design`** : Optimized for both mobile and desktop devices with touch-friendly controls
- **`Memory Training`** : Scientifically designed to improve working memory and concentration
- **`Instant Restart`** : Quick restart functionality to immediately start a new game
- **`Cross-Platform Compatibility`** : Works on all modern browsers and devices
- **`Lightweight Performance`** : Fast loading and smooth gameplay with minimal resource usage

## ⚙️ Usage

### Getting Started

1. **Visit the live demo** at the provided URL or run locally
2. **Click "Start"** to begin your first memory challenge
3. **Observe the sequence** carefully as colors light up
4. **Repeat the pattern** by clicking buttons in the correct order
5. **Progress through levels** as sequences become longer and more challenging

### Key Operations

- **Start Game**: Click the start button or press <kbd>Space</kbd> to begin a new game
- **Pattern Input**: Click colored buttons to repeat the displayed sequence
- **Restart**: Use the restart button after game over to play again immediately
- **Score Tracking**: Monitor your current score and try to beat your high score
- **Audio Control**: Game includes sound effects for enhanced experience

## ⬇️ Installation

### Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Max-Eee/Simon-Game
   cd "Simon-Game"
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   # Or use a local server for development
   ```

3. **Run with live server (optional)**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

### Production Deployment

1. **GitHub Pages deployment**
   - Repository is automatically deployed via GitHub Pages
   - Access at: https://max-eee.github.io/Simon-Game/

2. **Manual deployment**
   - Copy all files to your web server
   - Ensure proper MIME types for audio files

## 🔧 Technical Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Audio**: Web Audio API for sound effects
- **Styling**: Custom CSS with responsive design
- **Deployment**: GitHub Pages

## 📁 Project Structure

```
Simon-Game/
├── index.html           # Main HTML structure
├── styles.css          # Game styling and animations
├── script.js           # Core game logic
├── sounds/             # Audio effects
│   ├── red.mp3
│   ├── green.mp3
│   ├── blue.mp3
│   ├── yellow.mp3
│   └── wrong.mp3
└── README.md           # Project documentation
```
