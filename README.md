# MELONOMA_DETECTION_ASSIGNMENT
CNN based model to detect Melonama(type of cancer)

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Model 1: the training accuracy is increasing linearly over time, whereas validation accuracy stalls around 60% in the training process. Also, the difference in accuracy between training and validation accuracy is noticeable — a sign of overfitting.
- Model 2: we have added dropout layer since model 1 was overfitting, but both training and validation accuracy has reduced to 55 to 60 
- Model 3: in this model we used augmentor to fix the class imbalance issue and we were able to increase accuracy, but it is observed after 10 epochs validation loss didnt reduce and started to increase in small amount.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Numpy -- version -1.24.3
- Pandas -- version -1.4.2
- Matplotlib -- version -3.5.1
- TensorFlow -- version -2.14.0
- Augmentor -- version -0.2.12


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was given by UpGrad

