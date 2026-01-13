# ✨ Particle Morph Pro - Hand Gesture Controlled 3D Particle Engine

<div align="center">

![Particle Morph Pro](https://img.shields.io/badge/Particle%20Morph-Pro%20Edition-ff2d55?style=for-the-badge&logo=sparkles&logoColor=white)
![Version](https://img.shields.io/badge/Version-2.0.0-00f2ff?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-22c55e?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

[![Made with Three.js](https://img.shields.io/badge/Made%20with-Three.js-black?style=flat-square&logo=three.js)](https://threejs.org/)
[![MediaPipe](https://img.shields.io/badge/Powered%20by-MediaPipe-4285F4?style=flat-square&logo=google)](https://mediapipe.dev/)
[![TailwindCSS](https://img.shields.io/badge/Styled%20with-TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)

<br/>

**🎮 Control 20,000+ Particles with Your Hands in Real-Time!**

*An immersive 3D particle visualization experience powered by AI hand tracking*

<br/>

[🚀 Live Demo](#live-demo) • [✨ Features](#features) • [🎯 Gestures](#hand-gestures) • [📖 Usage](#usage) • [🛠️ Installation](#installation)

</div>

---

## 🎬 Preview

<div align="center">

```
    ✋ Hand Tracking + Skeleton Visualization
           ↓
    🎨 20,000+ Interactive Particles
           ↓
    💥 Gesture-Controlled Effects
           ↓
    🌈 Beautiful Morphing Shapes
```

</div>

---

## 🌟 Features

### 🖐️ AI-Powered Hand Tracking
| Feature | Description |
|---------|-------------|
| 🎯 **Real-time Detection** | MediaPipe powered hand tracking at 30+ FPS |
| 🦴 **Skeleton Visualization** | Colorful finger skeleton overlay on camera feed |
| 🎨 **Multi-finger Recognition** | Detects individual finger states accurately |
| 📱 **Cross-platform** | Works on Desktop & Mobile browsers |

### 🎨 Particle System
| Feature | Description |
|---------|-------------|
| ✨ **20,000+ Particles** | Smooth performance with thousands of particles |
| 🔄 **Spring Physics** | Realistic morphing with velocity-based animation |
| 🌈 **Rainbow Mode** | Continuous color cycling effect |
| 💫 **Additive Blending** | Beautiful glowing particle effects |

### 🎭 14 Unique Shapes
```
🌸 Flower    ❤️ Heart     ⭐ Star      ∞ Infinity
🦋 Butterfly 🌀 Spiral    👑 Crown     💎 Diamond
🧬 DNA       🌌 Galaxy    🌊 Wave      🔮 Sphere
📦 Cube      ⭕ Rings
```

### ⚙️ Customization Controls
- **Particle Size** - Adjust particle dimensions
- **Animation Speed** - Control morphing velocity
- **Trail Effect** - Configure particle trails
- **Boom Power** - Set explosion intensity
- **Hand Smoothness** - Fine-tune tracking sensitivity
- **Auto Rotate** - Toggle automatic rotation
- **Rainbow Mode** - Enable color cycling
- **Show Skeleton** - Toggle hand skeleton display

---

## 🎯 Hand Gestures

<div align="center">

| Gesture | Fingers | Action | Visual |
|:-------:|:-------:|:------:|:------:|
| ✌️ **Peace Sign** | 2 Fingers | **BOOM! 💥** | Particle Explosion |
| 🤟 **Three Fingers** | 3 Fingers | **360° Rotate 🔄** | Full Rotation |
| 👆 **Pointer** | 1 Finger | **Pointer Mode** | Precise Control |
| 🖐️ **Open Hand** | 5 Fingers | **Expand** | Particles Grow |
| ✊ **Fist** | 0 Fingers | **Shrink** | Particles Contract |

</div>

### Gesture Detection Details

```javascript
// Peace Sign (BOOM) Detection
✌️ = Index UP + Middle UP + Ring DOWN + Pinky DOWN

// Three Fingers (360°) Detection  
🤟 = Index UP + Middle UP + Ring UP + Pinky DOWN

// Fist Detection
✊ = All fingers curled (hand scale < 0.3)
```

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|:---:|:------:|
| `Space` | Trigger BOOM Effect 💥 |
| `R` | Random Shape 🎲 |
| `D` | Reset to Defaults ↩️ |

---

## 🛠️ Installation

### Option 1: Direct Use (No Installation)
Simply open `index.html` in any modern browser!

```bash
# Clone the repository
git clone https://github.com/SudhirDevOps1/particle-morph-pro.git

# Navigate to directory
cd particle-morph-pro

# Open in browser
open index.html
# or
start index.html  # Windows
```

### Option 2: Local Server (Recommended)
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

---

## 📖 Usage

### Getting Started

1. **Allow Camera Access** - Grant permission when prompted
2. **Position Your Hand** - Hold hand 1-2 feet from camera
3. **Watch the Skeleton** - Colored lines appear on your fingers
4. **Try Gestures** - Use peace sign, three fingers, fist, etc.
5. **Explore Shapes** - Click shape buttons at bottom
6. **Customize** - Use settings panel on left side

### Settings Panel

```
┌─────────────────────────┐
│ ⚙️ Controls             │
├─────────────────────────┤
│ Particle Size    [====] │
│ Animation Speed  [====] │
│ Trail Effect     [====] │
│ Boom Power       [====] │
│ Hand Smoothness  [====] │
├─────────────────────────┤
│ Auto Rotate      [ON ]  │
│ Rainbow Mode     [OFF]  │
│ Show Skeleton    [ON ]  │
├─────────────────────────┤
│ [💥 BOOM!]              │
│ [🔄 360° Rotate]        │
│ [🎲 Random Shape]       │
│ [↩️ Reset Default]      │
└─────────────────────────┘
```

---

## 🎨 Color Palette

<div align="center">

| Color | Hex Code | Preview |
|:-----:|:--------:|:-------:|
| Pink | `#ff2d55` | 🔴 |
| Cyan | `#00f2ff` | 🔵 |
| Yellow | `#ffcc00` | 🟡 |
| White | `#ffffff` | ⚪ |
| Green | `#22c55e` | 🟢 |
| Purple | `#a855f7` | 🟣 |
| Orange | `#f97316` | 🟠 |
| Rainbow | Animated | 🌈 |

</div>

---

## 🔧 Technical Stack

<div align="center">

| Technology | Purpose |
|:----------:|:-------:|
| ![Three.js](https://img.shields.io/badge/Three.js-black?style=flat-square&logo=three.js) | 3D Rendering & Particles |
| ![MediaPipe](https://img.shields.io/badge/MediaPipe-4285F4?style=flat-square&logo=google) | Hand Tracking AI |
| ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css) | Styling |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Core Logic |
| ![Lucide](https://img.shields.io/badge/Lucide-Icons-orange?style=flat-square) | Icons |

</div>

---

## 📱 Browser Support

| Browser | Support |
|:-------:|:-------:|
| Chrome | ✅ Full Support |
| Firefox | ✅ Full Support |
| Safari | ✅ Full Support |
| Edge | ✅ Full Support |
| Mobile Chrome | ✅ Full Support |
| Mobile Safari | ✅ Full Support |

---

## 📂 Project Structure

```
particle-morph-pro/
│
├── 📄 index.html          # Main application file
├── 📄 README.md           # Documentation (this file)
├── 📄 LICENSE             # MIT License
│
└── 📁 assets/             # (Optional) Additional assets
    ├── 📁 screenshots/
    └── 📁 demos/
```

---

## 🚀 Performance Tips

1. **Close other tabs** - Free up GPU memory
2. **Good lighting** - Helps hand detection accuracy
3. **Plain background** - Improves tracking stability
4. **Keep hand in frame** - Maintain consistent tracking
5. **Modern GPU** - Better particle performance

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

```bash
# Fork the repository
# Create your feature branch
git checkout -b feature/AmazingFeature

# Commit your changes
git commit -m 'Add some AmazingFeature'

# Push to the branch
git push origin feature/AmazingFeature

# Open a Pull Request
```

### Contribution Ideas
- [ ] Add more particle shapes
- [ ] Implement two-hand tracking
- [ ] Add audio reactivity
- [ ] Create preset themes
- [ ] Add particle physics modes

---

## 📜 License

<div align="center">

Distributed under the **MIT License**. See `LICENSE` for more information.

```
MIT License

Copyright (c) 2024 Sudhir

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
```

</div>

---

## 👨‍💻 Author

<div align="center">

### **Sudhir**

[![GitHub](https://img.shields.io/badge/GitHub-SudhirDevOps1-181717?style=for-the-badge&logo=github)](https://github.com/SudhirDevOps1)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-ff2d55?style=for-the-badge&logo=google-chrome&logoColor=white)](https://github.com/SudhirDevOps1)

<br/>

**Full Stack Developer | DevOps Engineer | Creative Technologist**

*Building innovative solutions at the intersection of AI and Web Technologies*

</div>

---

## 🙏 Acknowledgments

- [Three.js](https://threejs.org/) - Amazing 3D library
- [MediaPipe](https://mediapipe.dev/) - Powerful ML solutions
- [TailwindCSS](https://tailwindcss.com/) - Utility-first CSS
- [Lucide Icons](https://lucide.dev/) - Beautiful icons

---

## 📊 Stats

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/SudhirDevOps1/particle-morph-pro?style=social)
![GitHub forks](https://img.shields.io/github/forks/SudhirDevOps1/particle-morph-pro?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/SudhirDevOps1/particle-morph-pro?style=social)

</div>

---

<div align="center">

### ⭐ Star this repo if you found it useful!

<br/>

**Made with ❤️ by [Sudhir](https://github.com/SudhirDevOps1)**

<br/>

![Wave](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,19,20,24&height=100&section=footer)

</div>
