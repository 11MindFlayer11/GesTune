# Hand Gesture Volume Control

Control your system's volume using hand gestures via a webcam. This project uses OpenCV for video processing, MediaPipe for hand tracking (through a custom module), and Pycaw for controlling system volume on Windows.

---

## 🛠️ Features

- Real-time hand detection and tracking
- Gesture-based volume control using thumb and index finger distance
- Visual volume bar feedback on screen
- FPS display for performance monitoring

---

## 📦 Requirements

Install dependencies with pip:

```bash
pip install opencv-python mediapipe numpy pycaw comtypes
