# Flower Classification using CNNs

This repository contains code for classifying flowers from the IRIS Flowers Image dataset using Convolutional Neural Networks (CNNs). It includes implementations of both a custom CNN and the Transfer Learning method using VGG16.

## Dataset

The IRIS Flowers Image dataset can be downloaded from the following link: [IRIS Flowers Image dataset](https://drive.google.com/drive/u/0/folders/1sigV5_YrdewSDJ6OdK20B22CzeKNMh4b/)

The dataset is organized into three folders:
- iris-setosa
- iris-versicolor
- iris-virginica

Each folder contains images corresponding to the respective flower class.

## Requirements

To run the code, you need the following dependencies:
- Python (>=3.6)
- TensorFlow (>=2.0) or PyTorch (>=1.0)
- NumPy
- Matplotlib

## Instructions

1. **Download the dataset**: Download the IRIS Flowers Image dataset from the provided link.

2. **Prepare the dataset**: Organize the dataset into folders as mentioned above, with each folder containing images of a specific flower class.

3. **Open the IPython Notebook**: Open the notebook file `flower_classification.ipynb` using Jupyter Notebook or JupyterLab.   

4. **Run the cells**: Execute the cells in the notebook to load the data, preprocess it, define the model, train the model, and evaluate its performance.

5. **Evaluate the results**: Once the model training is complete, evaluate the performance using metrics such as accuracy, precision, recall, and F1-score.

## Files

- `CS21B2023_Q1.ipynb`: Implementation of the custom CNN model for flower classification.
- `README.md`: Documentation and instructions.
- Datasets and model can be accessed through below drive link.
## Acknowledgments

- [Keras](https://keras.io/) or [PyTorch](https://pytorch.org/) for deep learning framework.
- [IRIS Flowers Image dataset](https://drive.google.com/drive/u/0/folders/1sigV5_YrdewSDJ6OdK20B22CzeKNMh4b/) for providing the dataset.
