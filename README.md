### Vehicle Detection, Tracking, and Counting

This project detects, tracks, and counts vehicles (cars) in video footage using **YOLOv8** for object detection and **DeepSORT** for multi-object tracking. The system processes videos, identifies cars, tracks them across frames, and counts the total number of unique vehicles in real-time.

#### Features

- Detects cars (class ID 2 in YOLO) in video frames.
- Tracks vehicles across frames using DeepSORT.
- Displays bounding boxes with unique track IDs for each vehicle.
- Shows the total number of unique vehicles detected in the video.
- Outputs a video with annotations (bounding boxes and car counts).

