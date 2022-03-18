## Udacity's Data Scientist Nanodegree Capstone Project: Dog Breed Classifier

### Project Overview

This project uses Convolutional Neural Networks (CNNs) and transfer learning in order to build a pipeline to process real-world, user-supplied images. Convolutional Neural Networks (CNNs) are commonly used to analyse image data. Transfer learning is a technique that allows to reuse a model across different tasks. The objective is that given an image of a dog, the algorithm will identify an estimate of the canine’s breed, and if supplied with an image of a human, it will estimate the closest breed that the human image looks like. If it classifies it as neither a human, nor a dog, it will ask to try again or use another image.

Medium article link: https://medium.com/@zacharyphillips723/udacity-capstone-classify-dog-breeds-249e2e11e91

### Table of Contents

1. [Libraries](#libraries)
2. [File Descriptions](#files)
3. [Content](#contents)
4. [Findings](#findings)

### Libraries <a name="libraries"></a>

    Keras
    OpenCV
    Matplotlib
    Numpy

### File descriptions <a name="files"></a>

* dog_app.ipynb: Jupyter notebook containing the algorithm and process used to create it.
* dog_app.html: A copy of dog_app.ipynb in html format.
* Images: Images in jpg format used to test the algorithm's predictions.


### Contents <a name="contents"></a>

The project is organized along the following steps:

    Intro
    Step 0: Import Datasets
    Step 1: Detect Humans
    Step 2: Detect Dog
    Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
    Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
    Step 5: Write Your Algorithm
    Step 6: Test Your Algorithm

### Findings <a name="findings"></a>
* The model achieved a test accuracy of 81.22%, which was above the 60% established accuracy threshold.
* The model detected all the dog images correctly, although the breeds were incorrect. It also detected a dog for an image of a giraffe. One picture was correctly classified as neither dog nor human since it was a person wearing a helmet.
* The predicted breeds for the dogs could be considered similar to a degree, but both dogs included were mixed breeds. Maybe further data and more training can account for breeds or probabilities of the top two or three predicted breeds.
* The model could probably use more improvements with respect to noise, augmentation, and distance of the subject in the images.
