## Autonomous Patient Care Robot Using ROS2

## Description
The Autonomous Patient Care Robot is an innovative solution revolutionizing healthcare services by providing continuous, personalized care to patients within medical facilities. This robot combines cutting-edge technology, including the Robot Operating System (ROS2), computer vision, voice recognition, and a user-friendly interface, ensuring seamless and personalized care for patients.

## Prototpe Model
The video can be found here [video link](https://youtu.be/6Nv3aHWfnFs)

<img align="center" src="https://github.com/vimalgrace/patient_care_robot/assets/91270314/b19c905d-9ad7-462c-9be2-85d3eb4aef62"> 
 
## Block Diagram
![image](https://github.com/vimalgrace/patient_care_robot/assets/91270314/699f8426-6bd6-45ff-8229-1c1935a640dc)

## Technology Used 

## Hardware
- Raspberry Pi 4B (4GB RAM)
- Arduino Uno R3
- RPLIDAR A1M8
- N20 Micro Metal Gear Motors with Encoders
- L293D Motor Driver
- LM7805 Voltage Regulator
- Wheels (4cm diameter)
- Lithium-ion Battery (3.7 Volts)
- Connecting Cables

## Software
- Ubuntu 22.04 LTS
- Robot Operating System (ROS2) (Distro : Humble)
- Nav2 Stack
- Python
- C++
- Arduino Programming
- OpenCV for Computer Vision
  
## Packages Used:
- **ros2_control** for interfacing raspberry pi with arduino
- **slam_toolbox** for generating map
- **rplidar_ros** for publishing scan data from lidar
- **amcl** for localizing

## Controllers Used:
- **MPPI Controller** to effectively follow the path

## Usage 
The patient care robot is designed for seamless integration into healthcare settings. It autonomously manages medication schedules, continuously monitors patient vitals, and enables communication between patients and healthcare providers through a user-friendly interface.



