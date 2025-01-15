# MelanomaDetection_CaseStudy_C66
# CNN Assignment - Melanoma Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

## Conclusions
- Model1 is created with 3 Convolutional layers, Flatten layer and 2 Dense layer without any augmentation and dropout layer Training accuracy is 88 and Validation accuracy is 54
- After Model1 we clearly see overfitting
- For Model2 added Augmentation(with RandomFlip and RandomRotation) and dropout layer extra - Training accuracy is 54 and validation accuracy is 53
- Overfitting reduced but accuracy decreased after Model2
- For Model3 we analysed there is lot of class imbalance so we use Augmentor and increase each class with 500 images, So finally Model3 has 3 Convolutional layers, Flatten layer, 2 
  Dense layer and 2 Dropout layers.
- After Model3 we see training accuracy 90 and validation accuracy as 82, So clearly there is a great improvement in accuracy.
- Also more number epochs adds more complexity which is further increasing the accuracy.


## Acknowledgements
This assignment was done while doing EPGM in Artificial Intelligence and Machine Learning from IIIT Bangalore and Upgrad.




<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
