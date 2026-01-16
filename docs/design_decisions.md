# Design Decisions

## ROS Distribution
ROS 2 Humble was selected as the primary platform due to compatibility with Ubuntu 22.04 and its long-term support status.

ROS 1 is discussed only for conceptual comparison, as it is not officially supported on newer Ubuntu versions.

## Simulation-First Approach
The project prioritizes simulation to enable rapid experimentation without hardware constraints.

## Modularity
Each functional subsystem is isolated into a separate ROS package to improve maintainability and future reuse.

