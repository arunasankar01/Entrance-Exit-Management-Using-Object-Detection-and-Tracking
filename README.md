# entrance-exit-mgmt
A people counting method based on Haar-like detection and template-matching algorithm; The aim of the method is to count pedestrians that are in a metro station automatically using video surveillance camera or any other public forum

# Overview
The script entrance-exit-management.py is written in Python and uses various libraries and technologies to fundamentally behave as a people counter.

# Technologies Used
*OpenCV*: Utilized for video capture, image processing, and drawing on frames.
*dlib*: Employed for object tracking with correlation trackers.
*NumPy*: Used for numerical operations and array manipulation.
*Argparse*: Utilized for parsing command-line arguments for flexible configuration.
*imutils*: Helpful for resizing frames and handling video streams efficiently.
*Caffe Model*: The script employs the MobileNet SSD model for object detection.

#Functionality
*Object* Detection: Detects and tracks people in the video stream.
*Counting* Movements: Tracks movements of people, determining if they move up or down within the frame.
*Visualization*: Provides visual feedback with bounding boxes, centroids, and direction information on the processed video frames.
