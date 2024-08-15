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
- OpenCV (>=4.0) {4.5.5.64}
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

## Classification report
```bash
                precision    recall  f1-score   support

   with_mask       0.98      1.00      0.99       383
without_mask       1.00      0.98      0.99       384

    accuracy                           0.99       767
   macro avg       0.99      0.99      0.99       767
weighted avg       0.99      0.99      0.99       767
```

The classification report you provided is an evaluation summary for a face mask detection model. Here's a breakdown of the key metrics:

- **Precision:** Indicates the accuracy of the positive predictions. For both "with_mask" and "without_mask" classes, the precision is very high (close to 1.00), suggesting that when the model predicts a class, it is usually correct.

- **Recall:** Represents the ability of the model to capture all the relevant instances of a class. For both classes, recall is very high, indicating that the model identifies most of the instances of each class.

- **F1-Score:** The harmonic mean of precision and recall. It provides a balance between precision and recall. Both classes have a high F1-score, indicating a good balance between precision and recall.

- **Support:** The number of actual occurrences of the class in the specified dataset. The support values for both classes indicate a relatively balanced dataset.

- **Accuracy:** The overall accuracy of the model on the entire dataset. In this case, the accuracy is very high (0.99 or 99%), indicating that the model performs well on both classes.

- **Macro Avg:** The average of precision, recall, and F1-score across classes. In this case, it's 0.99, indicating good overall performance.

- **Weighted Avg:** The weighted average of precision, recall, and F1-score, considering the number of samples in each class. Similar to macro avg, it's 0.99, suggesting consistent performance across both classes.

Overall, based on this classification report, the face mask detection model appears to be highly accurate and balanced in its predictions.


## Project Structure
detect_mask_video.py: Main script for real-time face mask detection.
face_detector: Directory containing the pre-trained face detector model.
mask_detector.model: Pre-trained face mask detection model.
dataset: Directory containing the dataset used for training the mask detection model.
## Credits
This project uses the Real-Time-Face-Mask-Detection repository.


