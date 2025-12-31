PROJECT OVERVIEWS:

This project implements a real-time vehicle detection and counting system using YOLOv8 and OpenCV. The system processes a road traffic video, detects multiple vehicle types such as cars, buses, trucks, motorcycles, and bicycles, and counts vehicles moving in IN and OUT directions based on a virtual reference line.Using deep learning–based object detection, the system draws bounding boxes around detected vehicles, identifies their class, and increments the count when vehicles cross a predefined center line. This approach is useful for traffic monitoring, smart transportation systems, and urban planning.

PROBLEM STATEMENT:

Manual traffic monitoring is inefficient, time-consuming, and prone to errors. Traditional sensor-based systems are costly and difficult to maintain. There is a need for an automated, vision-based traffic analysis system that can accurately detect and count vehicles in real time using video data.

OBJECTIVES:

-To detect vehicles in real-time using a deep learning model

-To classify vehicles into different categories (Car, Bus, Truck, etc.)

-To count vehicles moving in IN and OUT directions

-To visualize vehicle movement using bounding boxes and center points

-To build a scalable solution for intelligent traffic monitoring

TECHNOLOGIES USED:

-Python – Core programming language

-OpenCV (cv2) – Video processing and visualization

-YOLOv8 (Ultralytics) – Object detection model

-NumPy – Numerical computations

-Pre-trained YOLOv8s Model – Vehicle detection

-MP4 Video Input – Road traffic footage

HOW IT WORKS:

-A traffic video is read frame by frame using OpenCV.

-YOLOv8 detects vehicles in each frame and returns bounding boxes.

-Only vehicle classes (car, bus, truck, motorcycle, bicycle) are filtered.

-The center point of each detected vehicle is calculated.

-A virtual vertical and horizontal reference line is drawn on the road.

-When a vehicle’s center crosses the line, it is counted as IN or OUT.

-Vehicle counts are displayed live on the video feed.

PROJECT STATUS:

Day 1: Problem Analysis & Requirement Gathering

Day 2: Environment Setup

Day 3: Video Processing

Day 4: Vehicle Detection

Day 5: Vehicle Tracking Logic

Day 6: Visualization & Counting

Day 7: Testing & Optimization



