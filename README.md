# Project Name
> In this assignment, We built a multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion


## Conclusions
* To overcome the issue of class imbalance, used Augmentor to add more samples across all classes so that none of the classes have very few samples.
* This Class reblance helped to solve the Model Overfitting.
* Final Traning Accuracy : 70% and validation accuracy : 62%

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas  - Version: 1.2.4
- Numpy - Version: 1.20.1
- matplotlib - Version: 3.3.4
- TensorFlow - Version: 2.9.0
- Augmentor


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
