# Image Colorization

## Overview
This project implements an image colorization model that converts grayscale images into colorized versions using deep learning techniques. The model is trained to predict plausible colors for black-and-white images based on learned patterns from a dataset of colored images.

## Motivation
Image colorization is a challenging problem in computer vision with applications in restoring old photographs, enhancing black-and-white films, and improving visual understanding for historical images. This project aims to automate the colorization process using deep learning, making it accessible and efficient.

## Features
- Converts grayscale images to color
- Uses deep learning (CNN-based architecture)
- Pre-trained model for faster inference(caffemodel)
- Supports batch processing of images

### Required Libraries:
- OpenCV
- NumPy
- Download a pre-trained model for the code or download the model from the link given in the code

## Model Details
The colorization model is based on a Convolutional Neural Network (CNN) trained on a large dataset of natural images. It learns to predict the a*b color channels from the L channel in the Lab color space.


