# Face-Tracking-Robot
A computer vision robot that detects and tracks faces in real time, combining camera input, embedded control, and motion response for interactive robotics applications.

## Overview
This project is a face-tracking robotic system developed through the Robotics and Automation Society at Texas State University. The platform uses a Raspberry Pi 5 for real-time vision processing and combines Python with OpenCV for face detection alongside C++ servo control for responsive tracking motion.

The system is designed to keep a detected face centered in view while also logging tracking performance for later benchmarking.

## Objective
The purpose of this project was to:
- detect and track faces in real time
- achieve responsive motion with less than 200 ms latency
- combine computer vision with servo-based actuation
- build modular integration between perception, control, and logging
- benchmark tracking accuracy through structured data collection

## Technologies Used
- Raspberry Pi 5
- Python
- OpenCV
- C++
- servo control
- SQL logging

## Features
- real-time facial tracking
- sub-200 ms response target
- Python-based computer vision pipeline
- C++ servo control integration
- modular system design
- SQL logging for accuracy benchmarking

## Skills Demonstrated
- computer vision
- embedded and robotics integration
- Python and C++
- motion control
- latency-aware system design
- performance benchmarking
- technical documentation

## System Workflow
1. The camera captures live image frames.
2. OpenCV detects a face within the frame.
3. The system calculates position error relative to the frame center.
4. Servo control commands reposition the robot or mounted camera.
5. Tracking data is logged for performance evaluation.

## Repository Contents
- face detection code
- servo control modules
- SQL logging scripts
- testing notes
- benchmarking results
- demo media

## Future Improvements
- improve tracking robustness under movement and lighting variation
- expand to multi-face selection logic
- reduce jitter in servo response
- add visual dashboard for benchmarking results

## Author
Franceli Gonzalez
Texas State University | Robotics and Automation Society
