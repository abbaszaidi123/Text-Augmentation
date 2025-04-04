# Augmentation
Deep convolutional neural networks have performed remarkably well on many Computer Vision tasks. \
However, these networks are heavily reliant on big data to avoid overfitting. \
Overfitting refers to the phenomenon when a network learns a function with very high variance such as to perfectly model the training data. 

---

## Increasing the amount and diversity of data.

* what do you do when you have limited data? 
  * Ans: Data Augmentation.

* What is Data Augmentation? 
  * Data augmentation is a technique of artificially increasing the training set by creating modified copies of a dataset using existing data. 
  * It includes making minor changes to the dataset or using deep learning to generate new data points.  

* Commonly used Augmentation Techniques \
  Some of the commonly used Image data augmentations techniques are:

  1. Flipping
      * This means flipping the image horizontally or vertically.
      
  2. Rotation
      * This means to rotate the image by a given angle in the clockwise or anticlockwise direction.
      
  3. Cropping
      * During cropping, a section of the image is sampled randomly.
      
  4. Brightness
      * Increase or decrease the brightness of the image.
      
  5. Scaling
      * Scaling Images can be scaled outward or inward. When scaled outward, the image size increases while the image size decreases when scaled inwards.
      
  6. Noise Addition
      * We can also add gaussian noise to the existing images.
---      
* Popular Image Augmentation packages

    * skimage
    * opencv
    * imgaug
    * Albumentations
    * Augmentor
    * Keras(ImageDataGenerator class)
    * SOLT
---
![vz7gkdD](https://github.com/RATHOD-SHUBHAM/Augmentation/assets/58945964/baf9e9d8-bcd3-4d59-ad87-9308b4d2d73d)
Image source: Kaggle

---
![download](https://github.com/RATHOD-SHUBHAM/Augmentation/assets/58945964/5d8f1a65-5d11-4dbd-8b2b-8116499067ed)
