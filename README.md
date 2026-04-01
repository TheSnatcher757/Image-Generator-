# GenArt - Procedural Image Generation Engine

A browser-based generative art tool that creates unique images using mathematical algorithms. Six generation modes, six color palettes, and fully adjustable parameters. No AI APIs, pure algorithmic art.

## Algorithms

- **Flow Field** - Thousands of particles trace paths through Perlin-like noise fields
- **Fractal Tree** - Recursive branching structures with natural variation
- **Particle Galaxy** - Spiral arm particle system simulating galactic structures
- **Wave Interference** - Overlapping sine wave patterns with phase modulation
- **Generative Maze** - Recursive backtracking maze generation with colored walls
- **Circle Packing** - Non-overlapping circle fill algorithm

## Features

- 6 procedural generation algorithms
- 6 color palettes (Neon, Sunset, Forest, Vapor, Mono, Fire)
- Adjustable density, complexity, and scale parameters
- Seed-based generation for reproducible results
- PNG download for any generated image
- Generation history with click-to-reload
- Custom noise functions (FBM, smooth noise)

## How It Works

Each algorithm uses deterministic pseudo-random noise functions seeded by an integer value. The same seed, algorithm, and parameters always produce the same output. The noise system uses fractional Brownian motion (FBM) built from layered smooth noise for organic-looking patterns.

## Tech

- React 18 with hooks
- HTML5 Canvas 2D rendering
- Custom noise and FBM implementation (no external libraries)
- All generation runs client-side in the browser

## Author

**Angel Nunez**

