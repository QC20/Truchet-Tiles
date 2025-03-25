# Truchet Tiles

An interactive web-based implementation of Truchet tiling - a mathematical pattern system that creates complex visual designs through simple tile rotations.

![Truchet Tiles Demo](https://github.com/yourusername/truchet-tiles/raw/main/demo.gif)

## Overview

This project brings the fascinating world of Truchet tiles to life through web technologies. Truchet tiling is a method of creating complex, maze-like patterns using simple tiles with fixed designs that can be rotated. In this implementation, each tile contains diagonal line segments that, when arranged and rotated properly, create intricate visual patterns that emerge from simplicity.

## Features

- **Dynamic Pattern Generation**: Automatically creates a responsive grid of Truchet tiles that adapts to any screen size
- **Interactive Rotations**: Hover over tiles to rotate them individually
- **Pattern Presets**: Click anywhere to cycle through different pattern arrangements
- **Autonomous Animation**: Tiles randomly rotate at varying intervals when not interacting with them
- **Responsive Design**: Automatically adjusts to window resizing

## Why Truchet Tiles Matter

For interaction designers, UX professionals, creative technologists, and HCI researchers, Truchet tiles represent a fascinating intersection of:

1. **Emergent Complexity**: Simple rules creating complex visual outcomes—a fundamental principle in both design and computation
2. **User Agency**: The delicate balance between algorithmic generation and user control
3. **Perceptual Psychology**: How humans perceive patterns and find meaning in visual arrangements
4. **Interactive Art**: Blurring the line between viewer and creator

## Technical Implementation

This project is built with vanilla JavaScript, CSS, and HTML, demonstrating that complex interactive experiences can be created without heavy frameworks.

### Key Technical Components:

- **CSS Gradients**: Uses radial gradients to create the distinctive line patterns in each tile
- **DOM Manipulation**: Dynamically generates the grid of tiles based on viewport dimensions
- **CSS Transforms**: Handles tile rotations with smooth transitions
- **Event Handling**: Manages user interactions and automatic animations
- **Responsive Design**: Adapts to different screen sizes through JavaScript recalculation

## How It Works

1. **Grid Generation**: The application calculates how many tiles are needed to fill the viewport
2. **Tile Creation**: Each tile contains two diagonal lines created using CSS radial gradients
3. **Initial Pattern**: Tiles are arranged in an alternating pattern by default
4. **Interaction Handling**: 
   - Hovering over a tile triggers its rotation
   - Clicking anywhere cycles through different pattern arrangements
   - Moving away from the page enables automatic random rotations

## Getting Started

```bash
# Clone the repository
git clone https://github.com/yourusername/truchet-tiles.git

# Navigate to the project directory
cd truchet-tiles

# Open in a browser
open index.html
```

No build tools or dependencies required—just pure web technologies!

## Customization

You can easily customize the appearance and behavior by modifying a few key variables:

- `elementScale` in app.js: Controls the size of individual tiles
- `--bg` and `--clr` in style.css: Change the background and line colors
- `--tc` in style.css: Adjust the thickness of the lines

## Research and Design Applications

This implementation can serve as:

- A teaching tool for explaining emergent complexity in design systems
- A prototyping platform for exploring pattern generation
- A research instrument for studying perceptual organization and user interaction
- An inspiration for generative design approaches

## Future Directions

- Implementing additional tile designs beyond the classic diagonal lines
- Adding color variation capabilities
- Exploring non-grid arrangements (hexagonal, triangular)
- Creating an export function for generated patterns
- Adding touch optimization for mobile experiences

## License

MIT License - See LICENSE file for details.

## Acknowledgments

This project draws inspiration from the mathematical work of Sébastien Truchet (1657-1729), who first studied these tiling patterns, and the modern explorations of algorithms and complexity by artists and designers working at the intersection of math and visual design.
