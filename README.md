# hand-gesture-recognition-opencv-mediapipe
# Hand Gesture Recognition using OpenCV and MediaPipe

This project uses **OpenCV** and **MediaPipe** to detect hand gestures in real-time via a webcam. It counts how many fingers are raised based on hand landmark detection.

## Features
- Real-time hand tracking
- Finger counting (0–5)
- OpenCV GUI

## How it works
Uses MediaPipe's `Hands` solution to detect 21 hand landmarks and compares positions of fingertip landmarks to determine whether a finger is raised.

## Requirements
Install with:
```
pip install -r requirements.txt
```

## Run the app
```
python hand_gesture.py
```

Press `ESC` to exit.

## License
MIT
