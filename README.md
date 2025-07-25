# CNN Cancer Detection Kaggle Mini Project

## Problem Statement and Data
### Problem and goal
This project addresses a binary image classification task using Convolutional Neural Networks (CNNs). The primary goal is to develop a deep learning model that can accurately identify the presence of metastatic cancer in small digital pathology images. These images, known as histopathologic scans, are small patches taken from much larger whole-slide images of lymph node tissue. To achieve this goal, the CNN model predict the probability that an image patch contains tumor cells.

### Performance evaluation
The performance of prediction model is evaluated using the AREA Under the ROC Curve (AUC).

### Data overview
- **Data source:** Publicly available from Kaggle Website: https://www.kaggle.com/c/histopathologic-cancer-detection/overview
- **Image dimension:** Each image is a color (RGB) image with dimensions of 96 x 96 pixels.
- **Variable and label:** The CSV test file contains an ID column (unique image filesname) and label (1=positive; 0=negative).
