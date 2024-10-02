# Car Counter Detection System

This project demonstrates a car counter system using **Python** and **YOLO v8** for object detection. The system tracks vehicles on **highways**, detecting and counting cars passing through a specific point.

## Output Video Preview

[![Car Counter Output](https://img.youtube.com/vi/7d29d478-fec9-41a3-bf37-39e672095bac/0.jpg)](https://github.com/user-attachments/assets/7d29d478-fec9-41a3-bf37-39e672095bac)

## Purpose

The purpose of this project is to automate the process of counting vehicles on highways. This is useful for traffic monitoring and analysis, helping in managing congestion and improving road safety.

## How It Works

1. **YOLO v8 Object Detection**: The system employs the **YOLO v8** model, which is a state-of-the-art deep learning model for real-time object detection. It analyzes video frames to identify and localize cars on the highway by drawing bounding boxes around them.

2. **Data Processing**: Each frame from the video feed is processed, and the model outputs the positions of detected vehicles. The model is optimized to handle varying lighting conditions and speeds of moving cars.

3. **Counting Logic**: The system uses a counting algorithm to keep track of cars passing a predefined line or region on the highway. It increments the count for each car detected crossing this line while ensuring that duplicates (cars detected multiple times) are filtered out.

4. **Output Display**: The real-time count of vehicles is displayed on the screen, allowing for immediate monitoring of traffic conditions.

## Author

**Mugunth Jai Harish S.**  
[LinkedIn](https://www.linkedin.com/in/mugunthjaiharishs/)
