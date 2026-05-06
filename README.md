# Quantum React | Interactive Reaction Engine

![Quantum React Interface](https://shahateqx.github.io/quantum-react-sX9/)

A high-performance, visually stunning reaction time testing application built with **Three.js** and modern web technologies. Experience a futuristic interface designed to push your reflexes to the limit.

## 🚀 Features

- **Interactive 3D Visualizer**: A dynamic Three.js "Reactor" core that pulses, rotates, and changes state based on game phases.
- **Precision Timing**: Uses `performance.now()` for high-resolution millisecond accuracy in measuring reaction speeds.
- **Dynamic Particle System**: Background particles that react to your interactions with bursts of color and speed.
- **Glassmorphism UI**: A sleek, modern interface with real-time blur effects and high-end typography.
- **Stats Tracking**: Automatically saves your best time and session history using `localStorage`.
- **Accessibility First**: Integrated ARIA live regions and keyboard support (Space/Enter) for an inclusive experience.
- **Responsive & Mobile Ready**: Fully optimized for touch interactions and variable screen sizes.

## 🎮 How to Play

1. **Initialize**: Click anywhere or press **Space** to start the sequence.
2. **Wait**: The system will enter the "Initializing" phase. The reactor will turn orange and contract, building tension.
3. **React**: When the signal turns **Green** and the reactor expands, click or press **Space** as fast as you can!
4. **Results**: Your reaction time will be displayed in milliseconds.
5. **Session History**: View your best time and recent performance at the top and bottom of the screen.

> [!WARNING]
> **Signal Lost**: If you react before the green signal, the sequence will fail. Precision and patience are key.

## 🛠️ Technical Stack

- **Structure**: Semantic HTML5
- **Styling**: Vanilla CSS3 with CSS Variables and Flexbox/Grid
- **Logic**: ES6+ JavaScript Modules
- **Graphics**: [Three.js](https://threejs.org/) (WebGL)
- **Post-Processing**: UnrealBloomPass for the cinematic glow effect
- **Fonts**: Google Fonts (Inter & Space Grotesk)

## 📁 Project Structure

```text
quantum-react-sx9/
└── index.html    # The monolithic single-file application
```

*Note: The project is designed as a portable, single-file application for ease of deployment and performance.*

## 🔧 Local Development

Since this project uses ES Modules and Three.js via import maps, it's recommended to run it through a local web server to avoid CORS issues with textures or modules.

**Using VS Code Live Server:**
1. Install the "Live Server" extension.
2. Right-click `index.html` and select **Open with Live Server**.

**Using Node.js (npx):**
```bash
npx serve .
```

## 📜 License

This project is open-source and available under the MIT License.
