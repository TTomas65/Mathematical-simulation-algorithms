# Mathematical Simulation Algorithms

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![p5.js](https://img.shields.io/badge/p5.js-ED225D?style=flat&logo=p5dotjs&logoColor=white)
![Interactive](https://img.shields.io/badge/Interactive-Visualization-FF6B6B)
![Math](https://img.shields.io/badge/Mathematical-Algorithms-4CAF50)

*Interactive visualization of mathematical algorithms*

This p5.js-based interactive web application presents dynamic drawings based on mathematical formulas. The application allows users to explore various mathematical patterns through real-time manipulation of parameters.
![Application Screenshot](pictures/screen_math01.jpg)

## Features

### Algorithm Selector
In the left control panel, you can choose from a drop-down list of existing functions. Each algorithm has its own trigonometric/parametric function and drawing scheme.

### Real-time Controls
- **Scale**: Zoom (0.2× - 3×)
- **Offset X/Y**: Horizontal and vertical offset (±1200 px)
- **Color**: Full color range (0 - 360° HSB), white at 0°

Each slider updates the display instantly, so you can experiment with the shape live.

### Code Display Panel
A panel above the canvas shows the original code of the selected algorithm (scrollable if longer). This makes it easy to copy or modify the formula.

### Canvas
The canvas is 1000 × 1000 px. In each frame, ~10,000-30,000 points are plotted taking into account the current parameters (time step t, magnification, offset, color), so the patterns are constantly "live".

## Project Structure

- **HTML + CSS**: Clean, dark theme interface with logo and fixed left-hand control panel.
- **JavaScript / p5.js**: A single sketch (`setup()` + `draw()`) that loads functions from an array of algorithms, making it easy to add new algorithms by simply inserting a new object.

## About

The program is designed to demonstrate, through spectacular animated examples, the visual richness of simple trigonometric and parametric functions - while allowing the user to experiment freely with scale, position, and color.

## Getting Started

1. Clone this repository
2. Open `2D_visualization_extend.html` in a modern web browser
3. Use the control panel to explore different algorithms and parameters

## Dependencies

- [p5.js](https://p5js.org/) - JavaScript library for creative coding
