# Melanoma Case Study


There are more than 200 distinct types of cancer. Melanoma is the most hazardous type of skin cancer out of 200. Clinical screening is the first step in the diagnostic process for melanoma, which is then followed by dermoscopic analysis and histological investigation. If melanoma skin cancer is detected early on, it has a high chance of recovery. Examining the afflicted area of skin visually is the initial step in diagnosing melanoma skin cancer. Dermatologists use a high-speed camera to capture dermatoscopic images of skin lesions; these images can diagnose melanoma with 65–80% accuracy without the need for extra technical assistance. After additional visual inspection by cancer treatment experts and the use of dermatoscopic pictures, the overall accuracy of the melanoma diagnosis prediction rate increased to 75-84%. 




## Study By
- Vasudha Srinivasaiah

## Table of Contents
* Problem Statement
* General Information
* Conclusions
* Technologies Used
* Acknowledgements

<!-- You can include any other section that is pertinent to your problem -->
## Problem Statement

Melanoma is a deadly disease, but if caught early, most melanomas can be cured with minor surgery. Image analysis tools that automate the diagnosis of melanoma will improve dermatologists' diagnostic accuracy. Better detection of melanoma has the opportunity to positively impact millions of people.
The project's goal is to develop an automated system for classifying skin lesions using photographs of the condition, based on image processing techniques.
    



## General Information

- Understanding

During the skin biopsy procedure, a portion of the skin lesion is removed by the dermatologist and examined under a microscope. Currently, scheduling an appointment with a dermatologist and receiving a biopsy report take at least a week. The objective is to provide the prediction model in order to reduce the existing gap to a few days. Using pictures of outlier lesions, the method employs Convolutional Neural Networks (CNN) to categorize nine forms of skin cancer. 
The project's major motivation is to apply advanced image categorization technologies to improve people's well-being. Computer vision has made significant advances in machine learning and deep learning, which are scalable across domains.

- Data Set :
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

   * Actinic keratosis
   * Basal cell carcinoma
   * Dermatofibroma
   * Melanoma
   * Nevus
   * Pigmented benign keratosis
   * Seborrheic keratosis
   * Squamous cell carcinoma
   * Vascular lesion
    
- Data Visualisation
Class 	No. of Image
    0 	actinic keratosis 	114
    1 	basal cell carcinoma 	376
    2 	dermatofibroma 	95
    3 	melanoma 	438
    4 	nevus 	357
    5 	pigmented benign keratosis 	462
    6 	seborrheic keratosis 	77
    7 	squamous cell carcinoma 	181
    8 	vascular lesion 	139

<img width="575" alt="image" src="https://github.com/user-attachments/assets/7f650943-4843-4ac2-b07e-8e39dcd398d6">


- Model Building & Evaluation

To classify skin cancer based on photographs of lesions and to improve classification accuracy and results, a customized CNN model is created. To overcome the issue of class imbalance, used a python package Augmentor (https://augmentor.readthedocs.io/en/master/) to add more samples across all classes so that none of the classes have very few samples.

Steps Involved:

    * Data Loading
    * Baseline Model Building
    * Training the Model and testing the model
    * Building an augmented model
    * Training the augmented model and testing the model
    * Countering Class Imbalance with augmentor
    * Building the final model
    * Training the final model and testing the model
    * Verifying the model


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

As the accuracy of the model increases, the loss decreases. The final model has an accuracy of 80% . The model is able to predict the class of the lesion with a 80% accuracy. Augmenting the data and countering class imbalance helped in improving the accuracy of the model.


## Technologies Used

- Python
- Tensorflow
- Keras
- Pandas - 2.0.3
- Numpy - 1.24.3
- Matplotlib - 3.7.2
- Seaborn - 0.12.2
- Plotly - 5.9.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This project is individual case study for an online advance course.
- https://www.geeksforgeeks.org/
- https://seaborn.pydata.org/
- https://plotly.com/
- https://pandas.pydata.org/
- https://learn.upgrad.com/
- https://scikit-learn.org/
- https://www.statsmodels.org/



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
