# Enhanced Face Detection

This project implements a multi-method face detection system using **Mediapipe**, **Dlib**, and **RetinaFace**. It is designed to detect faces and landmarks from live webcam video with preprocessing for low-light and high-contrast conditions.

## Features

- **Mediapipe Face Detection**: Detects faces with high accuracy and fast performance.
- **Dlib Face & Landmark Detection**: Detects faces and provides facial landmarks, drawing landmarks for eyes and other facial features.
- **RetinaFace**: Detects faces in every frame for improved robustness.
- **Frame Preprocessing**: Applies CLAHE and Gamma correction for low-light and high-contrast scenarios.

## Installation

To set up the environment and dependencies, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/enhanced-face-detection.git
   cd enhanced-face-detection
