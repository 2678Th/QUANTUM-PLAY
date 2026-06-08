# Quantum Playground: Double-Slit Experiment

A plain JavaScript browser project that visualises the double-slit experiment using HTML Canvas.

## What it does

This project simulates two visual modes:

1. **Observer off**: particles build a wave-like interference pattern on the detection screen.
2. **Observer on**: particles behave more like measured particles and cluster behind the two slits.

The aim is educational and visual. It is not a laboratory-accurate physics engine.

## Features

- Canvas-based animation
- Observer on/off toggle
- Adjustable particle burst size
- Adjustable particle speed
- Adjustable slit separation
- Adjustable wave strength
- Detection counter
- Pause and reset buttons
- Responsive dark science-inspired interface

## How to run

Open `index.html` directly in your browser.

For a local development server, you can also run:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Suggested improvements

- Add a short guided tutorial mode
- Add a graph beside the screen showing detection density
- Add sound effects for detections
- Add a 3D version using Three.js
- Add more modules such as Schrödinger’s Cat, Entanglement, and Uncertainty

## Project structure

```text
quantum-double-slit/
├── index.html
├── styles.css
├── src/
│   └── main.js
└── README.md
```
