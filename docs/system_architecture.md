# System Architecture

The system follows a modular ROS architecture separating description, simulation, and control.

## Core Components
- Robot description (URDF/Xacro)
- Simulation environment (Gazebo)
- Control interface via velocity commands

## Data Flow
User input or control logic publishes velocity commands:

cmd_vel → controller → simulated robot

Each component is isolated in its own ROS package to allow independent testing and future extension.

