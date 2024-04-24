# Dog Breed Image Classifier
![Testing model performance on pug input photo](https://github.com/chrisdutkie/dog_breed_image_classifier/blob/main/pug_test.png)
## Overview
This Python script makes use of TensorFlow’s built-in Convolutional Neural Network (CNN) functions to build, train, and validate a CNN model capable of classifying dog breeds based on an input photo. 

The model was trained on 1,737 dog photos taken from Google Images including Pugs (<3), Labradors, Cavaliers, Rottweilers, and Chihuahuas. Several data cleaning and augmentation techniques were used to bring the model’s accuracy from 50% to ~70%, with confidence rates as high as 99% for specified input photos (as seen above).

## Specifications
- Makes use of TensorFlow v2.15.0 (https://www.tensorflow.org/)
- Google Drive used for folder storage system
- Google Colab (L4 GPU) used for model training sequence
