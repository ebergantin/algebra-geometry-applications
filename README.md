# Algebra and Geometry – Computational Examples

Simple computational examples for a first-year **Algebra and Geometry** course in Industrial Engineering.

The notebooks are designed to show how basic concepts from linear algebra, geometry and numerical computation can be connected to simple real-world applications.

The examples are intentionally introductory and focus on visualization and intuition rather than on advanced numerical methods.

## Notebooks

### `images.ipynb`

A simple introduction to images as matrices (numerical arrays).

Topics include:

- matrices as grayscale images
- rows and columns as image pixels
- simple image manipulations
- grayscale and RGB images

### `linear_system.ipynb`

A short example on solving linear systems numerically.

Topics include:

- Gaussian elimination
- matrix representation of a linear system
- solving systems with `numpy.linalg.solve`
- solving larger systems computationally
- comparison between manual calculations and numerical computation

### `robotic_arm.ipynb`

A simple planar robotic arm described using vectors and coordinates.

Topics include:

- vector representation
- forward kinematics
- nonlinear systems
- inverse kinematics using numerical root finding
- multiple robot configurations reaching the same target

### `heart_activation.ipynb`

A simplified model of electrical activation in a discrete patch of cardiac tissue.

Topics include:

- discretization of a two-dimensional domain
- Euclidean distance between points
- propagation at constant velocity
- comparison between one and two pacing sites

This is a deliberately simplified model intended only to illustrate how elementary geometry can be used to build a small computational simulation.

## Requirements

The notebooks use Python and a few common scientific-computing libraries.

Install the dependencies with:

```bash
pip install -r requirements.txt
```