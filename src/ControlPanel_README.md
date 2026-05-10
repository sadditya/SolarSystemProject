# ControlPanel Class

## Overview
The `ControlPanel` class provides the user interface for controlling and managing the solar system simulation. It is a Swing GUI component that allows users to interact with the application.

## Purpose
- Present user controls for the simulation
- Handle user input (buttons, sliders, etc.)
- Allow adjustment of simulation parameters
- Enable/disable features or change visualization settings

## GUI Components (Typical)
- **Buttons**: Start, pause, stop, reset simulation
- **Sliders**: Adjust speed, zoom level, or other parameters
- **Labels/Displays**: Show current simulation state
- **Selection Controls**: Choose planets or viewing modes


## Responsibilities
- Capture user input
- Update simulation parameters
- Communicate with SolarSystem and AnimationPanel
- Provide feedback to the user

## Event Handling
- Contains inner classes (ControlPanel$1, $2, $3) for handling user events
- Action listeners for buttons and controls
- Change listeners for sliders

## Integration
Works with:
- **AnimationPanel**: Receives visualization updates, sends control parameters
- **SolarSystem**: Receives and applies user-controlled parameters
- **Main**: Integrated into the main application window

## Key Features
- Real-time parameter adjustment
- Simulation control (play, pause, speed)
- Interactive planet selection
- Settings management
