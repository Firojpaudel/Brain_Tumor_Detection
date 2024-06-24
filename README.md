# Brain Tumor Detection with MRI Images using PyTorch CNN

This project aims to detect brain tumors in MRI images using a Convolutional Neural Network (CNN) implemented in PyTorch.

## Overview
The CNN model is trained on a dataset of MRI images to classify images as either containing a tumor or not. The model achieves an accuracy of over 90%.

## Features
- Implementation of a CNN model in PyTorch for brain tumor detection
- Training and evaluation of the model using MRI images
- Visualization of feature maps of convolutional filters

## Installation
1. Clone the repository: `git clone https://github.com/Firojpaudel/Brain_Tumor_Detection.git`
2. Also you'll need to install pytorch and would suggest to create an environment 
3. And Install the required packages: `pip install -r requirements.txt` inside that environment
   > I used conda 

## Usage
1. Run `jupyter notebook` in the project directory
2. Open and run the `Brain_tumor_detection.ipynb` notebook
3. Follow the instructions in the notebook to train and test the CNN model

## Next Steps
- Address overfitting concerns due to the complexity of the model and limited dataset size
- Explore techniques such as data augmentation, regularization, or using a simpler model architecture
