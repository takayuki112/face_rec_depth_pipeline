# Face Recognition and Depth Estimation Pipeline
This repository contains an image processing pipeline that identifies a target face in a video stream and estimates the depth of the entire image.
The pipeline is implemented using teh following pretrained models -
1. YOLOv8 for person detection
2. SFaceNet for face recognition
3. MiDaS for depth estimation

## Things you can specify - 
- Input Video Source (or webcam)
- Target Face to Identify
- Output Video path

## Sample Output
![alt text](./outputs/sample.gif)

- In the above example, the target face is identified by a blue rectangle in the upper frame.
- The lower frame is a heatmap of the depth estimation of the entire image.
- When the recognised face moves towards or away from the camera, this change is recognised and a message pops up.

#### Applications
- This can be used in a variety of applications, including security, surveillance, monitoring, robotics and automation, etc.

