# Fire Detection Using CNN

## About
This project implements a Convolutional Neural Network (CNN) to detect fire in images and video streams. The model is trained on a custom dataset, utilizing image augmentation techniques to improve performance.

## Features
- Image classification of fire and neutral conditions.
- Real-time video analysis for fire detection.
- Visualization of training and validation accuracy/loss.

## Requirements
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib

## Installation
```bash
pip install tensorflow keras opencv-python numpy matplotlib
```

## Dataset Structure
Ensure your dataset is structured as follows:
```
dataset/
    Training/
        Fire/
        Neutral/
    Validation/
        Fire/
        Neutral/
```

## Usage
1. **Training the Model:**
   Run the training script to train the CNN model using the dataset.

2. **Testing with Images:**
   Use the provided test images to evaluate the model's performance.

3. **Real-time Detection:**
   Run the video detection script to monitor fire in live video feeds.

## Model Saving
The trained model is saved as `fire_model.h5` in the `models/` directory.
