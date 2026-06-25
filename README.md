# 🧬 DNA Viewer - Interactive 3D Visualization

<p align="center">
  <img src="screenshots/home.png" width="850" alt="DNA Viewer">
</p>

<p align="center">

![C](https://img.shields.io/badge/Language-C-blue.svg)
![OpenGL](https://img.shields.io/badge/OpenGL-Graphics-red.svg)
![GLFW](https://img.shields.io/badge/GLFW-Windowing-green.svg)
![GLEW](https://img.shields.io/badge/GLEW-Extensions-orange.svg)
![FreeGLUT](https://img.shields.io/badge/FreeGLUT-UI-purple.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey.svg)
![License](https://img.shields.io/badge/License-MIT-blue)

</p>

---

## 📖 Overview

**DNA Viewer** is an interactive **3D visualization application** developed in **C using OpenGL**. It demonstrates the structure of DNA through a fully rendered double helix while providing educational content and interactive learning tools.

The application allows users to explore DNA in real time with smooth rotation, zooming, animation, nucleotide selection, learning modules, and quizzes.

This project was developed as part of a **Computer Graphics & Visualization** course.

---

# ✨ Features

### 🧬 3D DNA Visualization
- Realistic DNA double helix
- Smooth OpenGL rendering
- Interactive camera controls
- Dynamic lighting
- Perspective projection

### 🎮 Interactive Controls
- Mouse drag to rotate
- Mouse wheel to zoom
- Atom selection
- Auto-spin animation
- DNA replication visualization

### 📚 Learning Mode
- DNA structure explanation
- Base pairing rules
- Purines vs Pyrimidines
- Sugar-phosphate backbone
- Major & Minor grooves
- DNA replication
- B-DNA overview

### 🧠 Quiz Mode
- Multiple choice questions
- Score tracking
- Educational explanations
- Interactive learning experience

### 🎨 Rendering Modes
- Standard View
- Learn Mode
- Groove Mode
- Animation Mode

### 🌙 UI Features
- Dark / Light theme
- FPS counter
- Information panel
- Status bar
- Base pair information
- Sequence viewer

---

# 📸 Screenshots

## Home Screen

```
Add image here:
screenshots/home.png
```

---

## DNA Viewer

```
Add image here:
screenshots/viewer.png
```

---

## Learn Mode

```
Add image here:
screenshots/learn.png
```

---

## Quiz Mode

```
Add image here:
screenshots/quiz.png
```

---

# 🛠 Technologies Used

- C99
- OpenGL
- GLFW
- GLEW
- FreeGLUT
- GCC

---

# 📂 Project Structure

```
DNA-Viewer/
│
├── dna_viewer.c
├── README.md
├── LICENSE
├── screenshots/
│   ├── home.png
│   ├── viewer.png
│   ├── learn.png
│   └── quiz.png
└── .gitignore
```

---

# ⚙ Installation

## Linux (Ubuntu / WSL)

Install dependencies

```bash
sudo apt update

sudo apt install \
libgl1-mesa-dev \
libglu1-mesa-dev \
libglew-dev \
libglfw3-dev \
freeglut3-dev
```

Compile

```bash
gcc -std=c99 -O2 \
-o dna_viewer dna_viewer.c \
-lGL -lGLEW -lglfw -lglut -lm
```

Run

```bash
./dna_viewer
```

---

## Windows

Install

- MinGW GCC
- OpenGL
- GLFW
- GLEW
- FreeGLUT

Compile using GCC

```bash
gcc dna_viewer.c -o dna_viewer ^
-lglfw3 ^
-lglew32 ^
-lopengl32 ^
-lfreeglut ^
-lgdi32
```

---

# 🎮 Controls

| Action | Control |
|---------|----------|
| Rotate | Left Mouse Drag |
| Zoom | Mouse Wheel |
| Select Base | Left Click |
| Replicate DNA | R |
| Auto Spin | Space |
| Change Mode | M |
| Change Theme | T |
| Reset View | V |
| Clear Replicas | C |
| Increase Speed | ] |
| Decrease Speed | [ |

---

# 🧬 DNA Information

The application demonstrates

- Double Helix Structure
- Complementary Base Pairing
- Hydrogen Bonds
- DNA Replication
- Purines & Pyrimidines
- Major & Minor Grooves
- Sugar-Phosphate Backbone

---

# 🚀 Future Improvements

- DNA sequence editing
- RNA visualization
- Protein synthesis simulation
- Molecular animation
- VR support
- PDB file loading
- Better shaders
- Texture mapping
- Modern OpenGL rendering

---

# 🎓 Educational Purpose

This project is intended for

- Computer Graphics
- Bioinformatics
- Molecular Biology
- Data Visualization
- Interactive Learning

---

# 👨‍💻 Author

**Mohit**

B.Tech Student

---

# ⭐ If you like this project

Give it a ⭐ on GitHub!
