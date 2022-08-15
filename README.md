# **Malaria Detection**

[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org)
[![streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)](https://streamlit.io/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io/)

An end-to-end Deep Learning project to detect Malaria in human Blood Cell

## **Problem Statement**
Malaria is a life-threatening disease caused by Plasmodium parasities, is still a severe health concern in large parts of the world especially the third world countries. Almost 2019 million cases of malaria, across 87 countries worldwide, were reported by World Health Organization (WHO) in the year de 2017. WHO designated South-East Asia, Eastern Mediterranean, Western Pacific, and the Americas as high risk zone. Malaria is curable and can be prevented if proper initiatives and approaches are taken effectively, which majorly relies on early diagnosis of malaria parasities.

In this project, we develop a Convolutional Neural Network model and Deploy it in a Streamlit web app to detect whether a cell is parasitized or not with malaria based in microscopic images.



## **Data Preparation**
The malaria dataset contain two folders:
  - Parasitized 
  - Unifected
With a total of 27,560 images

This dataset was taken from NIH Website: [Link](https://ceb.nlm.nih.gov/repositories/malaria-datasets/)

Data Preprocessing Steps:

- Split data into train and val set
- Data normalization[0,1]
- Data augmentation techniques applied:
  - image flipping
  - zoom
  - image rotation
  - Image brightness range

## **Modelling**
In this project I tasted the folling Convolutional Neural Network Architecture by transfer learning method:

 - MobileNetV2 (Pretrained with imginet images)

Fine Tune model Performnace: 93% (accuracy score metric)(MODIFY)

## **Deploy**
The Streamlit app was deployed on Streamlit Cloud

