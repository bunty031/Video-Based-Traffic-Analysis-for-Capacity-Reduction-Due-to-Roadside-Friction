# Video-Based-Traffic-Analysis-for-Capacity-Reduction-Due-to-Roadside-Friction

A traffic monitoring system that analyses road videos to detect and track vehicles, estimate their speed, identify illegal parking and wrong-way driving, and understand how these activities affect traffic flow and road capacity.

1. Project Overview

Traffic congestion is increasing due to roadside activities such as illegal parking, street vendors, and vehicles moving in the wrong direction. These activities reduce road capacity and disturb the smooth flow of traffic.

This project aims to develop a video-based traffic analysis system that monitors road conditions using computer vision and deep learning techniques. It detects and classifies vehicles, counts vehicles, estimates their speed, and identifies roadside issues such as wrong-way driving and illegally parked vehicles.

The system helps in understanding traffic conditions and provides useful information that can support better traffic management.

2. Objectives

The main objectives of this project are:

To develop a vehicle detection and classification system using YOLOv8.

To count vehicles from recorded traffic videos.

To identify roadside issues such as wrong-way driving and illegally parked vehicles.

To estimate the speed of vehicles using video data.

To analyze traffic conditions and understand how roadside activities affect road capacity.

3. Technologies Used

Technology

Purpose

Python

Main programming language

YOLOv8

Vehicle detection and classification

ByteTrack

Tracking vehicles across video frames

OpenCV

Video processing and frame extraction

NumPy

Numerical operations and calculations

Computer Vision

Traffic video analysis

Deep Learning

Automated vehicle detection

4. Key Features

Vehicle Detection: Detects vehicles from traffic videos using YOLOv8.

Vehicle Classification: Identifies different categories of vehicles.

Vehicle Counting: Counts the number of vehicles detected in the video.

Vehicle Tracking: Tracks vehicles across consecutive frames using ByteTrack.

Speed Estimation: Estimates vehicle speed based on movement between video frames.

Wrong-Way Detection: Identifies vehicles moving in the opposite direction using trajectory analysis.

Illegal Parking Detection: Identifies vehicles that remain stationary for a specified period.

Traffic Monitoring: Displays vehicle information and detected roadside issues.

5. Project Workflow

Input a recorded traffic video.

Extract frames from the video using OpenCV.

Detect and classify vehicles using YOLOv8.

Track detected vehicles using ByteTrack.

Count vehicles and estimate their speed.

Analyze vehicle movement to identify wrong-way driving.

Monitor stationary vehicles to identify possible illegal parking.

Display the analyzed traffic information and detected issues.

6. How to Run the Project

Prerequisites

Python installed on your system.

Required Python libraries.

Project source code.

Traffic video for analysis.

Step 1: Clone the Repository

git clone <your-repository-link>

Step 2: Open the Project Folder

cd <project-folder-name>

Step 3: Install Required Libraries

If your project contains a requirements.txt file, run:

pip install -r requirements.txt

Step 4: Run the Project

Execute the main Python file:

python <main-file-name>.py

Replace <main-file-name> with the actual name of your project's main Python file.

Step 5: Provide Traffic Video

Use the traffic video input supported by the project to start the analysis.

7. Project Scope

The project focuses on analyzing traffic conditions through video data and identifying issues that affect traffic flow. It can assist traffic authorities in understanding congestion and making better traffic management decisions.

The performance of the system depends on video quality, camera angle, lighting conditions, and available computing power. Future improvements may include using better detection models and integrating the system with real-time traffic monitoring and control systems.

8. Future Enhancements

Improve detection accuracy under different lighting and weather conditions.

Improve speed estimation using accurate camera calibration.

Identify additional roadside obstructions and traffic violations.

Integrate real-time traffic camera feeds.

Develop a dashboard for monitoring traffic conditions.

9. Conclusion

This project presents a video-based approach to traffic monitoring by combining vehicle detection, classification, tracking, counting, speed estimation, and roadside friction detection. It aims to provide a clearer understanding of traffic conditions and the factors that reduce road capacity.
