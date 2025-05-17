# Life: Survival

Life: Survival is a simulation of agents trying to survive in a dynamic environment. Agents move, seek food, form memories, reproduce, and evolve over time.

## Features

- Autonomous agents with evolving genes
- Resource management (food, energy, hunger)
- Simple reproduction and mutation logic
- Toggleable visual stats and behaviors
- Customizable simulation settings
- Interactive UI for adding entities and toggling modes
- Fullscreen and keyboard navigation support

## Tools

Available tools for interaction:
- Agent: Place a new agent on the grid
- Food: Drop food items
- Wall: Place impassable walls
- Water: Placeholder for future implementation
- Remove: Erase objects

## Controls

- Spawn agents in batches (1, 5, 10)
- Toggle UI overlays (vision, groups, energy, age)
- Pause or reset the simulation
- Fullscreen mode for immersive experience

## Agent Behavior

Each agent:
- Moves using simple steering behaviors
- Has energy, hunger, and age
- Can find and consume food
- Reproduces if energy allows
- Stores location memory and uses simple pathfinding
- Evolves over time via mutation

## Settings

Adjust parameters via the GUI:
- Agent attributes (speed, size, vision range, mutation rate, etc.)
- Food properties (size, energy value)
- World properties (grid size, food spawn rate)
- Drawing options (grid, vision, stats, etc.)

## How to Use

1. Open the HTML file in a modern browser.
2. Click buttons to place agents and resources.
3. Press "Fullscreen" for better experience.
4. Watch the agents interact, evolve, and survive.

## Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari)
- No server required — runs entirely client-side

## Future Plans

- Advanced pathfinding
- More complex agent memory and learning
- Predator-prey dynamics
- UI improvements and graph displays
