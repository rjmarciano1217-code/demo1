# Conway's Game of Life

A fully interactive implementation of Conway's Game of Life in a single HTML file. Features a toroidal (wraparound) grid, preset patterns, and intuitive controls.

## Features

- **Toroidal Grid**: Edges wrap around, allowing patterns to seamlessly traverse borders
- **Preset Patterns**: Quickly place Gliders, Lightweight Spaceships, Blinkers, and Pulsars
- **Free Drawing**: Toggle individual cells by clicking on the grid
- **Speed Control**: Adjust simulation speed from 1 to 60 generations per second
- **Real-time Statistics**: View current generation and live cell count
- **Keyboard Shortcuts**: Full keyboard control for fast interaction
- **Modern UI**: Dark theme with smooth animations and responsive layout

## How to Use

1. Open `index.html` in your web browser
2. Use the controls on the right to interact with the simulation:
   - **Start/Pause**: Begin or pause the simulation (Space)
   - **Step**: Advance one generation while paused
   - **Random**: Populate the grid with random cells (R)
   - **Clear**: Empty the grid (C)
   - **Speed Slider**: Adjust generations per second

## Pattern Tools

Select a pattern from the "Patterns" section, then click on the grid to place it:

- **Glider** (1): Classic moving pattern that repeats every 4 generations
- **LWSS** (2): Lightweight Spaceship, a 5-cell wide oscillator
- **Blinker** (3): Simple 3-cell oscillator with period 2
- **Pulsar** (4): Large 48-cell oscillator with period 3
- **Free Draw** (Click to toggle individual cells)

## Keyboard Controls

| Key | Action |
|-----|--------|
| **Space** | Start/Stop simulation |
| **R** | Randomize grid |
| **C** | Clear grid |
| **1** | Select Glider tool |
| **2** | Select LWSS tool |
| **3** | Select Blinker tool |
| **4** | Select Pulsar tool |

## Rules

Conway's Game of Life follows these rules:

1. Any live cell with 2–3 live neighbors survives
2. Any dead cell with exactly 3 live neighbors becomes alive
3. All other cells die or stay dead

## Technical Details

- **Grid Size**: 72×48 cells
- **Single File**: All HTML, CSS, and JavaScript in one file
- **No Dependencies**: Runs entirely in the browser with vanilla JavaScript
- **Canvas Rendering**: Uses HTML5 Canvas for efficient grid rendering
- **Performance**: Optimized for smooth 60+ FPS animation

## Getting Started

Simply open `index.html` in any modern web browser. No server or installation required.
