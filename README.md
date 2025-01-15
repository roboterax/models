# STAR1 Robot URDF Description

This repository contains the URDF description of the humanoid robot STAR1, developed by RobotEra, a leading company in humanoid robotics.

## Overview



- The robot has a total of 55 degrees of freedom (DOF), including the following parts:
  


  - Legs: 6 DOF × 2 = 12 DOF
  - Arms: 7 DOF × 2 = 14 DOF
  - Hands: 12 DOF × 2 = 24 DOF
  - Waist: 3 DOF
  - Head: 2 DOF

<!-- <img src="./images/zero_position.png" alt="zero_position" width="200">
<img src="./images/coordinate.png" alt="coordinate" width="200">
<img src="./images/upright.png" alt="upright" width="200">


| zero_pos                | coordinate                 | upright_pos                  |
|--------------------------|-------------------------|-------------------------|
| <img src="./images/zero_position.png" alt="zero_position" width="200"> | <img src="./images/coordinate.png" alt="coordinate" width="200"> | <img src="./images/upright.png" alt="upright" width="200"> | -->

<div style="display: flex; flex-direction: column; align-items: center;">
  <div style="display: flex; justify-content: center; align-items: center; margin-bottom: 10px;">
    <div style="text-align: center; margin: 0 10px;">
      <img src="./images/zero_position.png" alt="zero_position" width="200" style="margin: 0 10px;">
      <p>Figure 1: Zero Position</p>
    </div>
    <div style="text-align: center; margin: 0 10px;">
      <img src="./images/coordinate.png" alt="coordinate" width="200" style="margin: 0 10px;">
      <p>Figure 2: Coordinate System</p>
    </div>
    <div style="text-align: center; margin: 0 10px;">
      <img src="./images/upright.png" alt="upright" width="200" style="margin: 0 10px;">
      <p>Figure 3: Upright Position</p>
    </div>
  </div>
</div>




- When the robot is fully upright, the joint angles of the legs are as follows:

          | Joint Name                 | Angle (degrees) |
          |----------------------------|:---------------:|
          | left_hip_pitch_joint       |        30       |
          | left_knee_joint            |       -60       |
          | left_ankle_pitch_joint     |        30       |
          | right_hip_pitch_joint      |        30       |
          | right_knee_joint           |       -60       |
          | right_ankle_pitch_joint    |        30       |
          | Other leg joints           |         0       |



## Support & Contact

For technical support or business inquiries:
- Email: support@robotera.com
- Create an issue in this repository

## About RobotEra

RobotEra is dedicated to advancing humanoid robotics technology. Our XBot series includes:
- XBot-S: 1.2-meter tall humanoid robot
- XBot-L: 1.65-meter tall humanoid robot

We specialize in developing robust and versatile humanoid robots for real-world applications, with a focus on reliable sim-to-real transfer capabilities. 