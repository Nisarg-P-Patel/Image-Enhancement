# Image Enhancement

## Overview

This project implements deep learning techniques for image enhancement, focusing on **super-resolution** and **colorization** of low-resolution, black-and-white images using **Generative Adversarial Networks (GANs)**. The goal is to transform these images into high-resolution, colorized versions that are visually appealing.

## Features

- **Image Super-Resolution**: Enhances the resolution of images using GAN-based algorithms.
- **Image Colorization**: Converts black-and-white images to color using a regression model based on VGG-16.
- **Comparative Analysis**: Compares the results of GAN-based methods with traditional image enhancement techniques.

## Requirements

- Python 3.x
- TensorFlow or PyTorch
- OpenCV
- NumPy
- Matplotlib

## Dataset

The model is trained using a subset of **1,000 images** from the Imagenet dataset. It uses the original RGB images and their corresponding grayscale versions for training.

## Implementation Details

- **Colorization**: Uses a VGG-16 based regression model optimized with the Adam optimizer and Mean Squared Error (MSE) loss.
- **Super-Resolution**: Implemented using an ESRGAN model, leveraging pre-trained weights for improved performance.

## Practical Applications

- Medical imaging (e.g., detecting tumors in X-rays)
- Restoration of old photographs
- Enhancing visual data for research and analysis

## Future Scope

- Expand the dataset for training.
- Explore advanced GAN architectures for improved colorization and resolution.
- Apply enhancements to specific domains like medical imaging.

## Acknowledgements

This project was developed under the guidance of Dr. Ankit Sharma and supported by the Department of ICE and CSE at Nirma University, Ahmedabad, Gujarat, India.
