# Smart Industrial Material Transport Robot 

A simulated industrial material transport robot developed using Webots. This project demonstrates a robotic transportation system in a factory environment with an industrial-themed simulation world.

## Project Overview

The Smart Industrial Material Transport Robot is a Webots simulation project featuring a factory environment designed for material transportation tasks. The simulation includes an industrial floor layout, safety markings, storage racks, safety signs, and emergency exit markers.

## Features

- Industrial factory simulation environment
- Yellow safety lane markings
- Black and yellow perimeter safety stripes
- Storage racks with decorative cartons
- Colour-coded wall safety signs
- Emergency exit markers
- Industrial concrete floor with slab joints
- Open-frame industrial ceiling beams
- Overhead LED lighting
- Existing robot controller and navigation logic preserved

## Project Structure

```text
smart-industrial-material-transport-robot/
├── worlds/
│   └── factory_transport.wbt
├── controllers/
│   └── material_transport/
│       └── material_transport.py
└── README.md
```

## Technologies Used

- Webots
- Python
- Robotics Simulation
- Robot Navigation

## Requirements

- Webots R2023b or newer
- Python controller support in Webots

## How to Run

1. Download or clone this repository.
2. Extract the project folder if downloaded as ZIP.
3. Open Webots.
4. Open `worlds/factory_transport.wbt`.
5. Ensure the robot controller is set to `material_transport`.
6. Press **Reset** and then **Run** to start the simulation.

## Environment Details

The simulation environment includes decorative industrial elements such as safety markings, storage racks, safety signs, emergency exits, concrete flooring, ceiling beams, and LED panels.

The environmental decorations do not include collision geometry and therefore do not interfere with robot navigation.

## Project Information

- **Project Type:** Robotics & Automation Simulation
- **Simulation Platform:** Webots
- **Controller Language:** Python
- **Environment:** Industrial Factory
