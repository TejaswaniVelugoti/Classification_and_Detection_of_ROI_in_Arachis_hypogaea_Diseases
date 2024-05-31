# Classification and Detection of ROI in Arachis Hypogaea Diseases Using NASNetMobile 

## Introduction
This repository contains a deep learning model trained for the classification and detection of regions of interest (ROI) in diseases affecting Arachis hypogaea (peanut) plants. The model is intended to assist researchers and agricultural professionals in detecting and classifying peanut plant diseases efficiently.

## Model Architecture
The base model used for training is NASNetMobile, chosen for its robust performance in image classification tasks. Additionally, image processing techniques are used for segmenting the diseased regions.

## Dataset
The model was trained on a dataset consisting of images of peanut plants affected by certain diseases such as leaf spot and rust as well as healthy plants. The dataset was appropriately labeled for multi-class classification, covering different types of diseases.

## Training
The model underwent training utilizing transfer learning methodologies, whereby the pre-existing NASNetMobile architecture was fine-tuned with our dataset. During this training process, model parameters were optimized to minimize a selected loss function while striving to maximize accuracy. Additionally, image processing techniques such as Gaussian blur and adaptive thresholding were employed to isolate and segment the regions affected by disease.The classification task was performed, yielding graphical representations of the classification results.

## Performance
After training, the model achieved high accuracy on the validation dataset, indicating its potential effectiveness in detecting and classifying diseases in peanut plants.

## Usage
To use the model for detecting and classifying diseases in peanut plants, follow these steps:

1. Load the pretrained model NASNetMobile.
2. Preprocess input images to match the format expected by the model.
3. Use the model to predict the class of the disease and identify regions of interest (ROI) in the input images.

---

Feel free to further customize the content as per your project specifics.
