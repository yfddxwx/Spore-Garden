# Spore Garden

An interactive particle garden drawn with Canvas. Move your cursor or click to plant breathing lights.

![HTML](https://img.shields.io/badge/HTML-single--file-e34f26?logo=html5&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-8fffc0)

## Overview

**Spore Garden** is a single-file HTML interactive experiment. When your pointer moves across or clicks the canvas, glowing spore particles are born. Particles automatically connect to nearby neighbors and slowly fade away, forming a garden of light that keeps growing, breathing, and dissolving.

## Behavior

- Pointer move → continuously plants a few spores
- Pointer down → plants 18 spores at once
- Particles within 90px of each other are connected by a line
- Particle colors range randomly from teal-green to blue-purple
- Particles drift, flicker, and gradually fade out
- When fewer than 20 particles remain, new ones are seeded at random positions

## Usage

Just open `index.html` in a browser. No build step, no dependencies, no server required.

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
open index.html   # macOS
# or
start index.html  # Windows
