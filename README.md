### Description 
A simple hand tracking module for humans using OpenCV, Mediapipe and Python.

You can include [handTrackingModule.py](https://github.com/karishmashuklaa/hand-tracker/blob/master/handTrackingModule.py) file in any of your projects and get a fully functional
*single hand* tracker ✍

### Configuration Options
* static_image_mode - If set to false, the solution treats the input images as a video stream.
* max_num_hands - Maximum number of hands to detect. Default to 2.
* min_detection_confidence - Minimum confidence value from the hand detection model for the detection to be considered successful. Default to 0.5.
* min_tracking_confidence - Minimum confidence value from the landmark-tracking model for the hand landmarks to be considered tracked successfully. Default to 0.5.

To change / understand the configurations, you can visit [MediaPipe - Hand landmark model](https://google.github.io/mediapipe/solutions/hands)

