Sure, here's a draft for your README file for your ESENSE HAR repository. Please replace `[INFO]` sections with your own information.

---
# ESENSE HAR REPO

This repository contains code for Human Activity Recognition (HAR) using the ESENSE wearable sensor. We use two different methods to validate our models: Leave-One-Out cross-validation and Random Split.

## Requirements

- Python 3.x
- Scikit-learn
- NumPy
- pandas

## Dataset

We use the Dataset for Leave-One-Out cross-validation and my-data for random-split for Human Activity Recognition. 

## Methodology

We use the following two methods for model validation:

### Leave-One-Out Cross-Validation

In this method, we use all but one of the data instances to train our model, then validate the model on the left out data instance. This process is repeated such that each data instance is used exactly once for validation.

### Random Split

In this method, we randomly split our data into a training set and a test set. The model is trained on the training set, and validated on the test set.

## Results

The performance of our model was as follows:

- `[INFO]: Performance metrics when using Leave-One-Out Cross-Validation`
- RANDOM FOREST

- ![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/49465215-f319-4604-ac96-41957803fbab)

- SUPPORT VECTOR

- ![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/848a0aa6-b68a-41a6-a213-0036f8d65173)

- MLP CLASSIFIER

- ![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/a661fa0b-9b59-4f65-9685-118e233a7768)

- LOGISTIC REGRESSION

- ![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/4624b342-ec96-4608-9235-a03e0cde62f0)




- `[INFO]: Performance metrics when using Random Split`
- - RANDOM FOREST

- ![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/f9d965fe-1bc3-4b1c-9a05-43ed9755df86)

- ![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/a561b086-76af-4219-81f4-74b87c1078c6)



- SUPPORT VECTOR

-![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/39ff6a4a-f9e5-44d9-a9f6-f3809b6cb8d1) 

-![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/cb834154-af1f-4fd4-b124-23c75ec57c99)






- MLP CLASSIFIER

- ![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/d174e0c8-9aed-4b0a-8619-fe6bdf417401)

- ![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/141569cd-ce1f-4c68-a71b-3e7678d0c142)



- LOGISTIC REGRESSION

- ![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/e3d84e10-4976-4d96-a126-0344308059d3)

- ![image](https://github.com/Sheral123/E-SENSE-HAR/assets/90202819/d9e3d715-9068-4596-bc1f-f7ebd4b99d5d)




---

