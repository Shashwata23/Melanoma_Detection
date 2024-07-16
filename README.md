# Melanoma_Detection
CNN based Model for detection of Melanoma skin cancer. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Convolutional Neural Network (CNN) has been developed using Keras in Python programming language.  

- Project Background: Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- Business Problem: To develop a software that can predict the type of skin cancer based on the photograph of skin. 

- Dataset Source: International Skin Imaging Collaboration (ISIC)


## Technologies Used
- matplotlib  
- tensorflow  
- numpy
- pandas
- os
- glob
- PIL


## Conclusions
- The initial model was overfitting the data as evident from the training accuracy being much higher than the validation accuracy. 
- After implementing data augmentation and introducing dropouts in the model, the overfitting was resolved effectively.


## Acknowledgements
This project is part of the UpGrad coursework on Machine Learning and Deep Learning.


## Contact
Created by [@shashwata23] - feel free to contact me!


