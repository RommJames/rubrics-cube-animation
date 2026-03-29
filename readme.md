# Rubik's Cube Animation

A pure CSS and HTML implementation of a 3D animated Rubik's Cube. This project showcases two simultaneously rotating cubes — one spinning on the Y-axis and another on the X-axis — built entirely without JavaScript, using CSS 3D transforms and keyframe animations.

## 🎯 Project Description

This project renders a pair of 3D Rubik's Cubes directly in the browser using semantic HTML and CSS. Each cube is composed of six faces (front, back, left, right, top, bottom), with each face containing a 3×3 grid of colored tiles represented by `<span>` elements. The cubes rotate continuously and independently using CSS animations, demonstrating the power of CSS 3D transforms for visual effects.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Structure and markup of the cube faces and tiles |
| **CSS3** | 3D transforms (`rotateX`, `rotateY`), `perspective`, `@keyframes` animations, and cube face styling |
| **PHP** *(optional)* | Server-side icon inclusion via `include_once` (used in a broader project context) |

## 📁 File Structure

```
rubrics-cube-animation/
├── index.html   # HTML structure of the two animated cubes
├── style.css    # All 3D transforms, animations, and visual styling
└── readme.md    # Project documentation
```

## 🚀 Getting Started

Simply open `index.html` in any modern web browser — no build tools or dependencies required.

> **Note:** The PHP `include_once` snippet in `index.html` is part of a larger project context. It can be safely removed or ignored when running the file standalone.