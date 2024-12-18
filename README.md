# Voice-Controlled Hand Tracking Project

This project combines computer vision with hand tracking and gesture recognition to control system volume using hand movements. The project utilizes Python libraries such as `mediapipe`, `opencv`, and `pycaw` to detect and process hand gestures, calculate the distance between fingers, and map it to system volume levels.

---

## Features
- **Hand Tracking**: Detect and track hand landmarks in real-time using the Mediapipe library.
- **Gesture Recognition**: Measure the distance between the thumb and index finger to adjust volume.
- **Volume Control**: Leverage the `pycaw` library to directly manipulate the system volume.
- **Real-Time Performance**: Achieve smooth real-time performance using optimized hand tracking and frame processing.

---

## Project Files
- **`HandTrackingModule.ipynb`**: A Jupyter Notebook implementing the hand tracking module with Mediapipe. This serves as a reusable component for detecting and processing hand gestures.
- **`VolumeHandcontrol.ipynb`**: A Jupyter Notebook that demonstrates the full functionality of gesture-based volume control using the hand tracking module.

---

## Installation and Setup
### Prerequisites
Ensure the following tools are installed:
- Python 3.8 or later
- `pip` (Python package manager)

### Install Required Libraries
Activate your virtual environment (if applicable) and install the required libraries:
```bash
pip install opencv-python mediapipe numpy comtypes pycaw
