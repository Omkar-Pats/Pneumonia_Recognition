## Dataset
The dataset utilized in this study comprised a complete of 5,856 chest X-ray images divided into two sub-sets: a training set and a test set, each having three categories: Normal, bacterial and viral.

<img target="_blank" src="https://github.com/kalpesh22-21/NN-to-classify-Street-House-View-Numbers/blob/main/images.png" width=270>

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:**  CV2, numpy, sklearn, matplotlib, flask, tensorflow, tensorflow_lite, Keras.

## Project Flow
<img target="_blank" src="https://github.com/kalpesh22-21/NN-to-classify-Street-House-View-Numbers/blob/main/images.png" width=270>

### Data Augmentation.
<img target="_blank" src="https://github.com/kalpesh22-21/NN-to-classify-Street-House-View-Numbers/blob/main/images.png" width=270>

## Evaluation
We used Transfer Learning and trained different models on the dataset and monitored their loss and accuracy vs epoch as shown below

### Inception V3 Accuracy & Loss
<img target="_blank" src="https://github.com/kalpesh22-21/NN-to-classify-Street-House-View-Numbers/blob/main/NN%201.png" width=270>

### Mobile Net Accuracy & Loss
<img target="_blank" src="https://github.com/kalpesh22-21/NN-to-classify-Street-House-View-Numbers/blob/main/Table.png" width=270>

### Res Net Accuracy & Loss
<img target="_blank" src="https://github.com/kalpesh22-21/NN-to-classify-Street-House-View-Numbers/blob/main/NN%202.png" width=270>

### VGG 16 Accuracy & Loss
<img target="_blank" src="https://github.com/kalpesh22-21/NN-to-classify-Street-House-View-Numbers/blob/main/NN%202.png" width=270>

### Models Accuracies & Losses on Test Data
<img target="_blank" src="https://github.com/kalpesh22-21/NN-to-classify-Street-House-View-Numbers/blob/main/NN%202.png" width=270>

#### Thus the VGG 16 outperformed other models.
### Finaly we exported model a keras model & tflite model for mobile application.
