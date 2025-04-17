# Tracer UR5e Assembly

This repository contains the integration of the Tracer Agilex mobile robot with a column and UR5e robotic arm mounted on top. The integration provides a complete mobile manipulation platform.

## Overview

The Tracer UR5e Assembly combines:
- Tracer Agilex mobile robot base
- Custom mounting column
- Universal Robots UR5e robotic arm

## Features

- Complete URDF model of the integrated system
- MoveIt configuration (in development)
- ROS launch files for visualization and control

## Screenshots

![Tracer UR5e Assembly View 1](images/Screenshot%20from%202025-04-17%2015-28-36.png)

![Tracer UR5e Assembly View 2](images/Screenshot%20from%202025-04-17%2015-29-43.png)

## Usage

To launch the system in RViz:

```bash
roslaunch tracer_ur5e_assembly rviz_ur5_or_tracer.launch
```

## Development Status

- ✅ Complete URDF model
- 🔄 MoveIt configuration (in development)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [Agilex Robotics](https://www.agilex.ai/) for the Tracer mobile robot
- [Universal Robots](https://www.universal-robots.com/) for the UR5e robotic arm 