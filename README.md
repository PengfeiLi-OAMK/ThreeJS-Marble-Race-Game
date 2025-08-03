# 🏁 Marble Race

A physics-based 3D obstacle course game built with [React Three Fiber](https://github.com/pmndrs/react-three-fiber), [Rapier physics engine](https://rapier.rs/), and [Zustand](https://github.com/pmndrs/zustand).

Guide your marble through a randomized obstacle course full of moving challenges and reach the giant burger at the finish line!

## 🕹️ Gameplay

- Use **WASD** or arrow keys to roll the marble.
- Press **Space** to jump.
- Avoid obstacles like spinners, limbos, and axes.
- If you fall, the game restarts automatically.
- Your completion time is displayed on screen.
- Click "Restart" after finishing to generate a new level.

## 📸 Screenshot

![Marble Race Preview]<img width="960" height="446" alt="1754221522452" src="https://github.com/user-attachments/assets/9e8d203e-2e08-4b78-a806-05c74c23b3e7" />


## 🧱 Features

- Dynamic level generation with randomized obstacle blocks.
- Smooth camera tracking and controls.
- Real-time physics simulation using `@react-three/rapier`.
- Simple UI overlay with time and restart control.
- Clean state management with `zustand`.

## 🚀 Getting Started

### Prerequisites

- Node.js >= 18 recommended

### Installation

```bash
git clone https://github.com/PengfeiLi-OAMK/ThreeJS-Marble-Race-Game
cd 66-create-a-game-with-r3f
npm install
```

### Development

```bash
npm run dev
```

### Build

```bash
npm run build
```

## 🛠 Tech Stack

- React
- Three.js
- React Three Fiber
- Rapier Physics
- Zustand
- Vite

## 📁 Project Structure
```text
src/
├── Experience.jsx        # Main 3D scene with physics, lights, level, player
├── Interface.jsx         # HUD with time and restart button
├── Level.jsx             # Procedurally generated blocks and obstacles
├── Lights.jsx            # Directional and ambient lighting
├── Player.jsx            # Marble logic, movement, jumping, and camera control
└── stores/
    └── useGame.jsx       # Zustand store for game phases and timers
```
    
## 📦 Dependencies
See package.json for the full list, including:

@react-three/fiber

@react-three/rapier

@react-three/drei

zustand

three

vite

## 📝 License
This project is developed by Pengfei Li for learning and demo purpose. Have fun racing! 🏎️
