# CIFAR-10 Image Classification with Artificial Neural Network (ANN)

This repository contains code for implementing an Artificial Neural Network (ANN) to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. 

## Dataset

The CIFAR-10 dataset can be downloaded directly from Keras . It comprises 50,000 training images and 10,000 testing images. Each image is 32x32 pixels and has a color depth of 3 channels (RGB).

### Steps Followed for Model Implementation

1. **Data Preprocessing**:
   - Flatten the input image dimensions to 1D (32x32x3 = 3072 pixels).
   - Normalize the image pixel values by dividing by 255.
   - One-Hot Encode the categorical column for labels.

2. **Model Architecture**:
   - Implemented using the Sequential API in TensorFlow/Keras.
   - Fully connected layers (Dense layers) are used.
   - Activation function: ReLU for hidden layers, Softmax for output layer (multi-class classification).

3. **Training and Evaluation**:
   - The model is trained using the training data.
   - Evaluation is performed using the test data to assess model performance.
   
## Instructions for Use

 **Clone the Repository**:
``` git clone : https://github.com/DevanshL/Deep-Learning-Lab/tree/1ec7514219fadd519e1fec17bf2bfe6afa1b96a8/Lab4 ```

