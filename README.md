# Yoga Pose Recognition

This project aims to recognize various yoga poses using machine learning and computer vision techniques.

## Introduction

Yoga Pose Recognition is an application that leverages machine learning algorithms and computer vision to identify and classify different yoga poses. The project uses a dataset consisting of 25-second video clips capturing six yoga poses performed by multiple individuals. The videos are uniformly recorded at 30 frames per second (fps) and a resolution of 1280x720 pixels.

The primary objective is to classify yoga poses accurately and efficiently in real-time, enabling users to practice yoga with guidance or to monitor their yoga sessions.

## Features

- Real-time recognition of six different yoga poses.
- Pretrained machine learning model for accurate pose classification.
- Utilizes a sequence of 125 frames (5 seconds at 25 fps) for inference.
- Provides visual feedback of recognized yoga poses on live video frames.

## Requirements

- Python 3.x
- TensorFlow
- OpenCV
- MediaPipe
- Other dependencies (specified in requirements.txt)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/username/YogaPoseRecognition.git
