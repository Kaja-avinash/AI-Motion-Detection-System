# 🚀 AI Motion Detection System

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![OpenCV](https://img.shields.io/badge/opencv-4.7+-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![CI](https://img.shields.io/badge/build-passing-brightgreen.svg)

A real-time computer vision system that detects motion and captures image sequences at configurable intervals.

## 📌 Table of Contents
- [Features](#-features)
- [Installation](#-installation)
- [Configuration](#-configuration)

## ✨ Features
- **Intelligent Motion Detection**: Adaptive background subtraction algorithm
- **Periodic Capture**: Configurable time intervals (default: 10s)
- **Visual Analytics**: Real-time bounding boxes and status overlay
- **Cross-Platform**: Compatible with Windows, Linux, and macOS
- **Efficient Storage**: Timestamped output organization

## 💻 Installation

### Prerequisites
- Python 3.8+
- Webcam or video input source

### Setup
# Clone the repository
git clone https://github.com/yourusername/AI-MotionDetection.git

# Navigate to project directory
cd AI-MotionDetection

### ⚙ Configuration
## Modify config:

# detection:
  sensitivity: 25        # 1-100 (lower = more sensitive)
  interval: 10           # Capture interval in seconds
  min_area: 500          # Minimum contour area (pixels)

# storage:
  output_dir: ./captures # Output directory
  max_files: 100         # Maximum files to keep
