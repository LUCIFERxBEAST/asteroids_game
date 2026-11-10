# Asteroids

A classic 2D Asteroids arcade game clone built with Python and Pygame, featuring vector polygon rendering, custom physics-based movement, and dynamic object lifecycle management.

---

## Features

- **Vector Rendering:** Smooth line-drawn ship and procedurally rendered polygonal asteroids.
- **Physics & Movement:** Directional rotation, forward/reverse thrust with delta-time (`dt`) frame stabilization, and 2D velocity vectors.
- **Sprite Architecture:** Modular lifecycle management dividing entities into `updatable`, `drawable`, `asteroids`, and `shots` groups.
- **Spawning & Collision System:** Boundary-spawning asteroid field with circular bounding-box collision detection and splitting mechanics.

---

## Tech Stack

- **Language:** Python 3.13+
- **Framework:** Pygame
- **Environment & Package Manager:** `uv`

---

## Controls

| Key | Action |
| :--- | :--- |
| `W` | Move Forward / Thrust |
| `S` | Reverse Thrust |
| `A` | Rotate Left (Counter-clockwise) |
| `D` | Rotate Right (Clockwise) |
| `Space` | Fire Shot |

---

## Getting Started

### Prerequisites

Ensure you have [uv](https://docs.astral.sh/uv/) installed:

```bash
curl -LsSf [https://astral.sh/uv/install.sh](https://astral.sh/uv/install.sh) | sh
