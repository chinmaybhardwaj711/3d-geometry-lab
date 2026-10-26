# 3D Geometry Lab

An interactive browser-based learning project for 3D vectors and transformations, built with JavaScript and Three.js.

## Features
- Interactive 3D cube with X/Y/Z rotation and translation controls
- Orbit, zoom, and pan controls
- Toggle coordinate axes/grid and cube wireframe
- Vector A/B visualization
- Live vector magnitude, dot product, and vector addition calculations
- Responsive layout

## Run locally
Because this project uses JavaScript modules, run it through a local HTTP server rather than opening `index.html` directly.

### Option A: Python
```bash
python -m http.server 8000
```
Then open http://localhost:8000

### Option B: VS Code
Install the Live Server extension, right-click `index.html`, and select **Open with Live Server**.

The page loads Three.js from a CDN, so an internet connection is required.

## Concepts demonstrated
- 3D Cartesian coordinates
- Vector magnitude: `|A| = sqrt(x² + y² + z²)`
- Dot product: `A · B = AxBx + AyBy + AzBz`
- Translation and rotation about the X, Y, and Z axes
- Interactive 3D rendering and camera controls

## Before adding to a resume
Run and test the project, understand the math and code, take your own screenshots, and publish the repository. Do not claim features or expertise you cannot explain in an interview.
