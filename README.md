# Safe Turn – Velocity Control Using Lane Detection

## Table of Contents
Project Overview
Motivation
Features
System Architecture
Technologies Used
Installation
Usage
Demo
Results
Future Work
Contributors
License

## Project Overview
The Safe Turn – Velocity Control Using Lane Detection project is designed to enhance road safety by dynamically adjusting vehicle speed based on the curvature of the road. Utilizing advanced lane detection and computer vision techniques, the system provides real-time recommendations or automated control for safe driving speeds, especially on curved roads where the risk of accidents increases due to excessive speed.

## Motivation
Driving at unsafe speeds on curved roads is a significant factor contributing to road accidents. This project addresses the need for a real-time system that can accurately predict road curvature and adjust vehicle speed accordingly. By integrating lane detection with velocity control, the project aims to reduce accidents and improve overall driving safety.

## Features
Real-time Lane Detection: Uses computer vision techniques to detect lane markings and analyze road curvature.
Dynamic Velocity Control: Automatically adjusts vehicle speed based on the detected curvature to ensure safe navigation.
User Interface: Provides real-time feedback to drivers, displaying recommended speed limits based on road conditions.
Integration with Autonomous Driving Systems: Enhances autonomous driving capabilities by incorporating safety measures related to road curvature.

## System Architecture
The system architecture consists of several key components:

Lane Detection Module: Implements computer vision algorithms to detect lane markings and determine road curvature.
Curvature Estimation: Calculates the radius of curvature based on lane detection data.
Velocity Control Algorithm: Adjusts vehicle speed based on the curvature to maintain safe driving conditions.
User Interface: Displays recommended speed limits to the driver and provides alerts when necessary.

## Technologies Used
Programming Languages: Python
Libraries: OpenCV, NumPy, TensorFlow/PyTorch (for deep learning models), Matplotlib
Deep Learning Models: Convolutional Neural Networks (CNNs) for lane detection
Development Tools: Jupyter Notebook, PyCharm, Git

## Installation
To set up the project on your local machine, follow these steps:
git clone https://github.com/yourusername/safe-turn-velocity-control.git
pip install -r requirements.txt
python main.py

## Usage
After installation, you can run the system by executing the main script. The system will capture video input (from a camera or video file), detect lanes, estimate the road curvature, and display the recommended safe speed on the user interface.

## Demo
Include a short demo video or GIF showing the system in action. Provide links to any recorded demonstrations or screenshots that showcase the key features.

## Results
Summarize the results of your project, including:

## Accuracy of lane detection.
Effectiveness of velocity control in different road conditions.
Comparative analysis with existing systems.

## Future Work
Integration with Vehicle Systems: Extend the project to control actual vehicle speed using hardware integration.
Enhanced Lane Detection: Improve lane detection accuracy under various lighting and weather conditions.
Expansion to Complex Road Scenarios: Adapt the system for more complex driving environments, including intersections and multi-lane highways.

## Contributors
Khushi Kharate - Project Lead and Developer

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
