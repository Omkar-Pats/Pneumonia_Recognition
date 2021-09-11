
## Project Overview:
To detection Pneumonia we need to detect Inflammation of the lungs. 
In this project, we built an algorithm to detect a visual signal for pneumonia in medical images i.e. to automatically locate lung opacities on chest radiographs.

## Dataset
The dataset utilized in this study comprised a complete of 5,856 chest X-ray images divided into two sub-sets: a training set and a test set, each having three categories: Normal, bacterial and viral.

<img target="_blank" src="https://github.com/kalpesh22-21/Pneumonia_Recognition/blob/main/Pneumonia Types of XRAYS.png" width=400>

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:**  CV2, numpy, sklearn, matplotlib, flask, tensorflow, tensorflow_lite, Keras.

## Project Flow
<img target="_blank" src="https://github.com/kalpesh22-21/Pneumonia_Recognition/blob/main/Flow%20Chart.jpg" width=500>

### Data Augmentation.
<img target="_blank" src="https://github.com/kalpesh22-21/Pneumonia_Recognition/blob/main/Augmentation.png" width=900>

## Evaluation
We used Transfer Learning and trained different models on the dataset and monitored their loss and accuracy vs epoch as shown below

## Inception V3 Accuracy & Loss

<img target="_blank" src="https://github.com/kalpesh22-21/Pneumonia_Recognition/blob/main/Inception%20V3%20Accuracy.jpg" width=400>

## Mobile Net Accuracy & Loss

<img target="_blank" src="https://github.com/kalpesh22-21/Pneumonia_Recognition/blob/main/Mobile%20Net%20Loss%20%26%20Accuracy.jpg" width=400>

## Res Net Accuracy & Loss

<img target="_blank" src="https://github.com/kalpesh22-21/Pneumonia_Recognition/blob/main/ResNet%2050%20Accuracy%20%26%20Loss.jpg" width=400>

## VGG 16 Accuracy & Loss

<img target="_blank" src="https://github.com/kalpesh22-21/Pneumonia_Recognition/blob/main/VGG%2016%20Model%20Accuracy%20%26%20Loss.jpg" width=400>

### Models Accuracies & Losses on Test Data
<img target="_blank" src="https://github.com/kalpesh22-21/Pneumonia_Recognition/blob/main/Test Results.png" width=270>

#### Thus the VGG 16 outperformed other models.
### Finaly we exported model a keras model & tflite model for mobile application.
