# 🪙 Coin Detection using OpenCV

A simple computer vision project that detects and counts coins using OpenCV in both images and webcam stream.

---

## Features
- Coin detection in static images
- Real-time detection using webcam
- Circle detection using OpenCV (Contours / HoughCircles)
- Image preprocessing pipeline

---

## Techniques Used (OpenCV)
- cv2.cvtColor (Grayscale conversion)
- Gaussian Blur (Noise reduction)
- Canny Edge Detection
- cv2.findContours
- cv2.dilate / morphology operations
- cv2.HoughCircles
- cv2.drawContours / cv2.circle

---
## Installation

```bash
pip install opencv-python numpy matplotlib
