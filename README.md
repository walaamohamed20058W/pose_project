# Pose Project - Real-time Pose Estimation

This project demonstrates real-time human pose estimation using MediaPipe and OpenCV.
It tracks body landmarks and displays them on the webcam feed in real-time.

Installation:
python -m venv mp_env
mp_env\Scripts\activate
python -m pip install --upgrade pip
pip install mediapipe opencv-python

Usage:
python pose_test.py
- The webcam will open and start detecting pose landmarks in real-time.
- Press ESC to exit.

Project Structure:
pose_project/
pose_test.py      # Main Python script
README.md         # Project description

Notes:
- Make sure to use Python 3.11 for compatibility with MediaPipe on Windows.
- Ensure the virtual environment is activated before running the script.
