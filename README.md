# Real Time Feature Matcher
This project is a real-time object detection system using Python, OpenCV, and ORB feature matching. It compares a static input image (content.jpg) with live webcam footage to detect and highlight matches using FLANN-based matcher. Keypoints are drawn on the screen to visualize the detection in action.

--
# 🔍 Real-Time Object Detection using ORB & FLANN

This project is a real-time object recognition system built with **Python** and **OpenCV**. It uses **ORB (Oriented FAST and Rotated BRIEF)** for feature detection and **FLANN-based matcher** to identify and match keypoints between a static input image and a live webcam feed.

---

## 🎯 Features

- Real-time object recognition using webcam
- Keypoint detection using ORB
- Fast and accurate matching using FLANN matcher
- Visual matching with line connections between keypoints
- Dynamic output display with frame-by-frame matching

---

## 🛠️ Technologies Used

| Tool/Library     | Description                          |
|------------------|--------------------------------------|
| Python 3         | Main programming language            |
| OpenCV           | Computer vision and image processing |
| NumPy            | Numerical operations                 |

> ⚙️ Internally, OpenCV uses **C++** for high-performance operations.

---

## 📁 Project Structure

```bash
├── content.jpg               # Input image used for detection
├── object_detection.py       # Main script to run
├── README.md                 # You're reading it ❤️
