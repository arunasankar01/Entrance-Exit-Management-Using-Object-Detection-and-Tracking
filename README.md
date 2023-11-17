# Entrance-Exit Management using Video Processing (Object detection, Object tracking)
A people counting method based on Haar-like detection and template-matching algorithm; The aim of the method is to count pedestrians that are in a metro station automatically using video surveillance camera or any other public forum

## Overview
The script entrance-exit-management.py is written in Python and uses various libraries and technologies to fundamentally behave as a people counter.

## Technologies Used
1. ***OpenCV***: Utilized for video capture, image processing, and drawing on frames.
2. ***dlib***: Employed for object tracking with correlation trackers.
3. ***NumPy***: Used for numerical operations and array manipulation.
4. ***Argparse***: Utilized for parsing command-line arguments for flexible configuration.
5. ***imutils***: Helpful for resizing frames and handling video streams efficiently.
6. ***Caffe Model***: The script employs the MobileNet SSD model for object detection.

## Functionality
1. ***Object Detection***: Detects and tracks people in the video stream.
2. ***Counting Movements***: Tracks movements of people, determining if they move up or down within the frame.
3. ***Visualization***: Provides visual feedback with bounding boxes, centroids, and direction information on the processed video frames.
