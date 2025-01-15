# STAR1 Robot URDF Description

This repository contains the URDF (Unified Robot Description Format) description of the STAR1 humanoid robot.

STAR1 is developed by RobotEra, a leading company in humanoid robotics. This URDF model represents RobotEra's XBot series humanoid robot.

## Overview

STAR1 is a humanoid robot with the following key features:

- Full humanoid body structure including:
  - Head with neck (yaw and pitch)
  - Dual arms with 7 DOF each
  - Waist with 3 DOF (pitch, roll, yaw)
  - Bipedal legs with 6 DOF each
  - Hands with end effectors

## Joint Configuration

### Head
- Neck Yaw: ±1.57 rad
- Neck Pitch: -0.17 to 0.54 rad

### Arms (Left and Right)
Each arm has 7 joints:
- Shoulder Pitch: ±2.79 rad
- Shoulder Roll: -0.24 to 1.83 rad (Left), -1.83 to 0.24 rad (Right)
- Arm Yaw: ±2.79 rad
- Elbow Pitch: -2.36 to 0.79 rad
- Elbow Yaw: ±2.62 rad
- Wrist Pitch: ±1.57 rad
- Wrist Roll: ±1.75 rad

### Waist
- Waist Pitch: -1.05 to 0.09 rad
- Waist Roll: ±0.26 rad
- Waist Yaw: ±1.57 rad

### Legs (Left and Right)
Each leg has 6 joints:
- Hip Roll: -0.21 to 1.22 rad (Left), -1.22 to 0.21 rad (Right)
- Hip Yaw: -0.52 to 1.22 rad (Left), -1.22 to 0.52 rad (Right)
- Hip Pitch: -1.57 to 1.4 rad
- Knee: -1.1 to 1.31 rad
- Ankle Pitch: -0.66 to 1.22 rad
- Ankle Roll: ±0.31 rad

## File Structure
- `urdf/l3_with_hand_fixedpin_xml.urdf`: Main URDF description file
- `meshes/`: Directory containing STL files for visual and collision geometries

## Dependencies
- ROS (Robot Operating System)
- xbot_description package

## Usage
The URDF can be used for:
- Robot visualization
- Kinematic and dynamic simulation
- Motion planning
- Control system development

## Notes
- All joint limits and dynamics parameters are specified in the URDF
- Mesh files are referenced relative to the package path
- Inertial properties are defined for all links 

## Support & Contact

For technical support or business inquiries:
- Email: support@robotera.com
- Create an issue in this repository

## About RobotEra

RobotEra is dedicated to advancing humanoid robotics technology. Our XBot series includes:
- XBot-S: 1.2-meter tall humanoid robot
- XBot-L: 1.65-meter tall humanoid robot

We specialize in developing robust and versatile humanoid robots for real-world applications, with a focus on reliable sim-to-real transfer capabilities. 