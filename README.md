# Melanoma Detection

## Introduction
> Melanoma is a skin cancer disease which is caused by changes in the properties of normal skin cells to
> become infectious, in which cells will continue to divide into abnormal shapes that are
> uncontrolled due to DNA damage.
> It can be deadly if not detected early. It accounts for 75%
of skin cancer deaths. The objective is to build a CNN based model which can accurately detect melanoma. A solution which can evaluate images and alert the dermatologists
about the presence of melanoma has the potential to reduce a lot of manual effort needed
in diagnosis.

## Multi-class classification problem
The following types of skin cancer diseases are present in the dataset : actinic keratosis, basal cell carcinoma, dermatofibroma, melanoma, nevus, pigmented benign keratosis, seborrheic keratosis, squamous cell carcinoma, vascular lesion

## Model Building
The entire code is divided into three parts
- Model 1 : A baseline model which will try to learn from the images present in the dataset.
- Model 2 : To prevent overfitting of the model, dropouts are added after each convolution+pooling layer
- Model 3 : Due to limited number of training images, the model doesn't generalize well. Used the Augmentor library to create transformations of train dataset with each class containing 500 images.

## Observations
The final model is able to learn from the augmented images with an improved accuracy.

## Contact
Created by [@encrypted-yknev](https://github.com/encrypted-yknev) - feel free to contact me!
