
# Hand Gesture Volume Control

A **Hand Gesture Volume Control** system allows users to control their device's volume using simple hand gestures. Using a camera and computer vision, the system detects the user's hand and tracks the distance between the thumb and index finger. Increasing the distance raises the volume, while decreasing it lowers the volume.

### Features

* Touch-free volume control
* Real-time hand gesture detection
* Simple and intuitive interaction
* Uses computer vision and hand tracking

### Technologies Used

* Python
* OpenCV
* MediaPipe
* Pycaw

### How It Works

1. The camera captures the user's hand.
2. MediaPipe detects and tracks hand landmarks.
3. The distance between the thumb and index finger is calculated.
4. The distance is mapped to the system volume level.
5. The volume changes in real time based on the gesture.
