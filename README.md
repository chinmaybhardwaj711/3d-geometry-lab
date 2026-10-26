
# 3D Geometry Lab

An interactive 3D mathematics visualizer built with JavaScript and Three.js. Explore vectors, rotation matrices, and homogeneous coordinate transformations.

## Features

- Interactive 3D cube with X, Y, and Z rotation controls
- Translation controls for moving objects in 3D space
- Orbit camera controls for viewing the scene from different angles
- 3D vector visualization for vectors A and B
- Vector magnitude, dot product, and vector addition calculations
- Live 3 × 3 rotation matrix
- Live 4 × 4 homogeneous transformation matrix
- Transformed point calculations using rotation and translation
- Wireframe and coordinate-axis controls

## Technologies

- JavaScript (ES modules)
- Three.js
- HTML5 and CSS3
- Git and GitHub

## Run Locally

You need Python or another local HTTP server and an internet connection to load Three.js from its CDN.

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

```bash
python -m http.server 8000
```

4. Open http://localhost:8000 in your browser.

Alternatively, use the VS Code Live Server extension.

## Mathematics Demonstrated

### Vector magnitude

`|A| = sqrt(x² + y² + z²)`

### Dot product

`A · B = AxBx + AyBy + AzBz`

### Point transformation

`P' = R P + t`

Here, `R` is the rotation matrix and `t` is the translation vector.

The homogeneous transformation matrix combines rotation and translation into a single 4 × 4 matrix.

## Future Improvements

- Visual explanation of matrix multiplication
- Additional transformation types
- Automated tests for mathematical calculations
