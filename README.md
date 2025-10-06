## Live Face Detection (OpenCV)

This Python script performs real-time face detection using your webcam and OpenCV's Haar Cascade Classifier.

### How It Works

- Captures video from your default webcam.
- Uses OpenCV's Haar Cascade Classifier to detect faces in real-time.
- Draws blue rectangles around detected faces in the video stream.
- Press `q` to quit the webcam display window.

### Requirements

- Python 3.x
- OpenCV (cv2)

#### Install dependencies:

### Usage

1. Save the script as `live_face_detection.py`.
2. Run the script:
3. A window will open showing your webcam feed with real-time face detection.  
- Faces will be highlighted with blue rectangles.
- Press `q` to quit and close the window.

### Notes

- Make sure your system has a working webcam.
- This script uses the built-in `haarcascade_frontalface_default.xml` included with OpenCV.
- Useful for learning and quick experiments with computer vision.

