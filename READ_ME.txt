                                      --------------------------------------------              
                                           U-Net Image Segmentation Project
                                      --------------------------------------------

This project implements a "U-Net convolutional neural network" for semantic image segmentation using TensorFlow and Keras.  
The model was trained on the [Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/) to segment pets (dogs and cats) from the background and tested on custom images.

---------------------------------------------------------------------------

## Project Overview

- Title: U-Net for Image Segmentation  
- Author: BOUGHERARA Khawla  
- Academic Year: 2024 / 2025  

-----------------------------------------------------------------------------

## Objectives

- Preprocess, resize, and normalize image data
- Apply basic data augmentation techniques (random horizontal flip)
- Build and train a U-Net model using Keras and TensorFlow
- Visualize training results (loss and accuracy)
- Evaluate the model on unseen personal test images

---

## Tools & Libraries

- Python 3.x  
- TensorFlow 2.x  
- Keras (via TensorFlow)  
- TensorFlow Datasets (`tfds`)  
- NumPy  
- Matplotlib  
- Pillow (PIL)

All required libraries are available by default in Google Colab.*

---

## Dataset

This project uses the "Oxford-IIIT Pet Dataset", loaded directly in the notebook via `tensorflow_datasets`.  
The dataset includes pet images and segmentation masks that label each pixel as background, pet, or border.

Dataset is not stored in this repository. It is downloaded automatically at runtime.

---

## How to Run the Project

1. Open the notebook [`Unet_khawla.ipynb`](./Unet_khawla.ipynb) in [Google Colab](https://colab.research.google.com)
2. Run all cells in sequence
3. Upload your own test images to the Colab environment
4. Observe the model’s predictions and visualizations at the end of the notebook

---

## Learning Outcome

This project introduced me to deep learning techniques applied to computer vision.  
It helped me understand the U-Net architecture, image preprocessing, semantic segmentation, and best practices for evaluating AI models.

---

## License

This project is academic. If you wish to reuse it, please provide appropriate citation and credit.

---
