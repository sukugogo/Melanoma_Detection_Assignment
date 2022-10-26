# Melanoma_Detection_Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- The purpose of this project/assignment is to build a CNN based model which can accurately detect melanoma. Melanom, a type of skin cancer, accounts for 75% of skin cancer deaths and can be deadly if not detected early. 

- The dataset used consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Conclusions
- Without a dropout rate and given set of sample images, the initial model was overfitting
- With a dropout rate of 0.2, the overfitting was reduced but the accuracy on the train (58%) and test data (56%) was still low
- Using an Augmentor to reduce the class imbalance (class sample size = 500) improved the accuracy of the model slightly by  (train (63%) and test (57%) )
- For the final model, epochs = 30 was used as the sample data size increased post usage of Augmentor


## Technologies Used
- Pandas
- Numpy
- Matplotlib
- Keras
- TensorFlow
- Augmentor


## Contact
Created by [@sukugogo] - feel free to contact me!
