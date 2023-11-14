# Real-Time-Face-Mask-Detection

## Overview

This project aims to detect whether a person is wearing a face mask or not in real-time using computer vision techniques. It combines a pre-trained face detector with a face mask classifier to analyze video streams from a webcam.

## Features

- Real-time face mask detection.
- Displaying bounding boxes and labels indicating whether a person is wearing a mask or not.
- User-friendly interface.

## Prerequisites

Make sure you have the following dependencies installed:

- Python (>=3.6)
- TensorFlow (>=2.5)
- OpenCV (>=4.0)
- Imutils
- Numpy

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```
## Usage
### Clone the repository

```bash
git clone https://github.com/yourusername/Face-Mask-Detection.git
cd Face-Mask-Detection
```
### Install dependencies:
```bash
pip install -r requirements.txt
```
### If you have downloaded file then load the files directory in the codes for loading dataset

### Run the face mask detection script:
```bash
python detect_mask_video.py
```
### Press 'q' to exit the application.

## Project Structure
detect_mask_video.py: Main script for real-time face mask detection.
face_detector: Directory containing the pre-trained face detector model.
mask_detector.model: Pre-trained face mask detection model.
dataset: Directory containing the dataset used for training the mask detection model.
## Credits
This project uses the Real-Time-Face-Mask-Detection repository.


