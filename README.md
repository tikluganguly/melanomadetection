# Melanoma Detection Assignment

> In this assignment, we have built a multiclass classification model using a custom convolutional neural network in TensorFlow.

**Problem statement:** To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- The initial dataset contains 2353 images of various malignant and benign oncological diseases
- To process the data the following steps were taken
  - Load the data into training and validation dataset.
  - we createed the initial model by using this data and found the model is overfitting
  - after that we reacreated the model by adding dropout and normalization.
  - still we did see some overfitting
  - finally we augmented the data using augmetor and added 500 samples per class to get a better model.
- The model is designed to detect skin cancer from image.
- We are using the International Skin Imaging Collaboration (ISIC) dataset

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- The intial samples has a very skewed data with overwhelming number of image for melanoma but all other classes had very little data.
- Due to this imbalance it was difficult to have a proper model. The model was always overfitting on training set and performing bad on testing set.
- augmenting the data really helped in makign a better model

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- tensorflow 2.12
- matplotlib 3.8
- numpy 1.23
- pandas 2.2
- python 3.11

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

Give credit here.

- We used code from [image classification](https://www.tensorflow.org/tutorials/images/classification) sample of tensorflow.
- This project is submitted as part of [upgrad IITB ML and AI course](https://learn.upgrad.com/course/5796/segment/51401/308369/935431/4668705).

## Contact

Created by [@tikluganguly] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
