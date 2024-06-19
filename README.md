<div align="center">
	<img src="https://github.com/Sebatik/Machine-Learning/assets/108218931/7fff1820-5995-4686-82a8-2a13e0f0e336">
</div>

# Batik Image Classification
Developing a deep learning model for Batik Pattern Image classification using Tensorflow: Creating a Convolutional Neural Network (CNN) with transfer learnings model to Classify 15 Batik pattern around indondonesia Using Tensorflow.

## Project Overview
We will develop a deep learning model using the tensorflow library that allows users to identify the type of batik pattern of the clothes they have by sending a photo of the clothes to our application and then the photo will be classified based on the batik pattern that matches the clothes. Users will get information on what batik pattern on their clothes such as pattern  name,  pattern origin, history.


## Dataset Information
The data set used in the development of this Deep Learning model consists of images that display Indonesian batik patterns and are organized into 15 categories.
15 Batik Category :
- DKI Ondel - Ondel
- Bali Barong
- Bali Merak
- Jawa Barat Megamendung
- Jawa Timur Pring
- Kalimantan Dayak
- Madura Mataketeran
- Maluku Pala
- Papua Asmat
- Papua Tifa
- Papua Cendrawasih
- Solo Parang
- Yogyakarta Kawung
- Sulawesi Selatan Lontara
- SumateraUtara Boraspati
### Dataset Link
https://drive.google.com/drive/folders/1C-U_XrEXcy3_MmfSbTXyiDjWlRDQGM4I?usp=sharing

## What Inside In Notebook?
- EDA
- Data Augmentation
- EffecientNetB3 (Transfer Learning)
- Inception (Transfer Learning)
- Exepction (Transfer Learning)

## Requirements 
- os
- Matplothlib
- Numpy
- Keras
- Tensorflow
- Sklern

## Documentation
- Conduct Machine Learning Model Research
- Collecting Batik Dataset
- Data Generator & Data Augmentation
- Develop machine learning model with CNN (Convolutional Neural Network) using EfficientNetB3, InceptionV3 & Exception architecture
- Train the model 
- Evaluate the machine learning model
- Testing the model by uploading new test data that the model has never seen before
- Convert model to h5 & Json format

## Results
### EffecientNetB3
The EffecientNetB3 model reached a result Val_accuracy of 96% on the test dataset. The training and validation loss/accuracy plots are found below.
![image](https://github.com/Sebatik/Machine-Learning/assets/108218931/8903b00f-efb2-4d1d-91ad-e810f8d255f9)

### InceptionV3
The InceptionV3 model reached a result Val_accuracy of 86% on the test dataset. The training and validation loss/accuracy plots are found below.
![image](https://github.com/Sebatik/Machine-Learning/assets/108218931/307e9f38-a554-417a-af40-27ae089705a9)

### Xception
The Xception model reached a result Val_accuracy of 88% on the test dataset. The training and validation loss/accuracy plots are found below.
![image](https://github.com/Sebatik/Machine-Learning/assets/108218931/c12cff0a-a164-4869-a5bf-d19bfa81ef86)






