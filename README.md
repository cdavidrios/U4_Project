# U4_Project: Alzheimer's Dementia Classification from Magnetic Resonance Imaging

This repository contains experiments for the classification of different Alzheimer's dementia stages from Magnetic Resonance Imaging using Deep Learning Techniques. The data was downloaded from [Kaggle](https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images). The data has four classes (Non demented, Very Mild Demented, Mild Demented, Moderate Demented) of images both in training as well as a testing set. Each image has a size of 208x176 pixels.

## Guideline
You can run each notebook in Google Colab.

## Content
The proposed work was divided in 4 experiments: 

**Experiment1** We designed 4 differents architectures for Convolutional Neural Networks to classify the Dementia stages in Alzheimer taking into account the original 4 classes. Due to the low performance of these experiments, for the next 3 experiments, we only consider the first 3 classes (we excluded the Moderate Demented class).

- In the second section, we used a TensorFlow Hub model to classify in two different ways the stages of Alzheimer: 1) using classic SVM classifier and 2) using fully connected layers. 

- Finally, in the last section we performed Transfer Learning from AlexNet.

Experiment1
