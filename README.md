# Face Mask Image Classification
## Overview
This is my first image classification project, which I created to practice my deep learning and computer vision skills by using a pre-trained VGG16 model in TenserFlow and Keras to classify an image of a person with and without a face mask.
## Dataset
The dataset that I used in this project is from Kaggle Face Mask Detection Dataset: https://www.kaggle.com/datasets/omkargurav/face-mask-dataset
## Prerequisites
To run this project, you will need the following libraries:
- TensorFlow/Keras
- Scikit-learn
- Numpy
- Matplotlib
- OpenCV
- Pandas
  
You can install these libraries by using:
```
pip install opencv-python tensorflow numpy matplotlib scikit-learn pandas
```

## Steps in project
1. Import necessary libraries that we work with.
2. Organize data into train, valid, and test directories by moving images into train, valid, and test directories, with 500 images per class for training, 100 per class for validation, and 50 per class for testing.
3. Prepare our image by using Keras ImageDataGenerator to create batches of data from the train, valid, and test directories and preprocessing our image for use with the VGG16 model.
4. Load the VGG16 model and fine-tune it to classify the two output classes: with_mask and without_mask.
5. Train the fine-tuned VGG16 model using the prepared data.
6. Use the trained model to predict classes for the test batches.
7. Evaluate the model using a confusion matrix and a classification report to measure accuracy and other metrics.
8. Display sample test images and their predictions.
9. Test model with some real images from internet to make sure that it can classify real images outside the dataset.
10. Save model.
## Model Result
This project achieves 98% accuracy and precision.
## Link to model file
https://drive.google.com/file/d/1tS_TC4SQ0oXqlhjRPN3benujt51Z0Nhp/view?usp=drive_link
