# MarsRobot

A low-cost Mars rover prototype developed as an engineering project.

## Project aims

- Design and build a mobile rover within a limited budget.
- Implement remotely controlled movement and telemetry.
- Develop a ROS 2 software architecture.
- Simulate the robot using Gazebo.
- Investigate autonomous navigation and obstacle detection.
- Collect environmental data using onboard sensors.
- Develop a camera-based optical spectrometer.
- Record, process and analyse scientific measurements.

## Architecture

The project is divided into several subsystems:

| Subsystem | Responsibility |
|---|---|
| `mars_robot_bringup` | Launch and configure the complete robot |
| `mars_robot_description` | URDF/Xacro model, geometry and TF |
| `mars_robot_control` | Motion control and odometry |
| `mars_robot_hardware` | Physical hardware interfaces |
| `mars_robot_interfaces` | Custom ROS 2 messages, services and actions |
| `mars_robot_navigation` | Mapping, localisation and navigation |
| `mars_robot_perception` | Camera and computer vision |
| `mars_robot_spectrometer` | Optical spectrum acquisition and processing |
| `mars_robot_sensors` | Environmental and motion sensors |
| `mars_robot_system` | Diagnostics and system state |
| `mars_robot_data` | Scientific data recording and export |

## Technology

- ROS 2
- C++
- Python
- Gazebo Sim
- RViz
- URDF / Xacro
- SDF
- YAML
- Linux
- Git

## Repository layout

- `src/` — ROS 2 packages
- `simulation/` — Gazebo environments and assets
- `hardware/` — electronics, firmware and bill of materials
- `mechanical/` — CAD, drawings and engineering calculations
- `config/` — shared configuration
- `tools/` — development and analysis tools
- `tests/` — testing
- `docs/` — engineering documentation

## Status

Currently in the initial software architecture and development environment setup phase.

## Licence

See `LICENSE`.
