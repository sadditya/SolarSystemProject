# Planet Class

## Overview
The `Planet` class represents an individual planet or celestial body in the solar system. It stores planetary properties and handles orbital calculations.

## Purpose
- Model a single planet with its properties
- Store planetary data (name, size, orbital parameters, position)
- Calculate planetary position and movement
- Provide data for rendering and physics calculations

## Key Properties (Typical)
- **Name**: Planet identifier
- **Position**: Current x, y coordinates
- **Velocity**: Movement vector
- **Mass**: For gravity calculations
- **Radius**: Visual size
- **Orbital Parameters**: Distance from sun, orbital speed, angle

## Responsibilities
- Maintain planetary state
- Update position based on orbital mechanics
- Provide data for visualization
- Handle collision detection (if applicable)

## Usage
Planet objects are created and managed by:
- **SolarSystem**: Maintains collection of planets
- **AnimationPanel**: Renders planets
- **ControlPanel**: Displays/controls planetary properties

## Key Methods (Typical)
- `update()`: Update planet position
- `getPosition()`: Return current location
- `getProperties()`: Return planet data
- `setOrbit()`: Configure orbital parameters
