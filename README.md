# Signature Detection, Extraction, and Translation

![Screenshot 2023-10-02 201703](https://github.com/EthanFlores1/practice/assets/110417575/c11c8cff-7174-486f-9deb-2bbeef96cbef)

## Table of Contents:
- Background & Dataset
- Workflow
- Technologies and Libraries
- Challenges
- Author Info

## 1. Background & Dataset
Digital signatures have been rapidly evolving as new technologies have allowed for document sharing and signing to become online. However, with a signature, it might not be apparent who signed it due to the variability in the appearance of the signature. To address this, we have created a machine learning model to detect the position of the signature and extract it into a snipper which has also been cleaned. To see who signed it, the snippet will be sent over to a translation model which will translate the signature into plain English.

 The [dataset](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps) we used was from Kaggle which contains images of documents each signed by different individuals.

## 2. Workflow
The overall workflow of the project went as following:
- Find viable data sets
- Detect the location of a signature and extract it into a snipper
- Clean the image of any background noise
- Send the image over to a translation model which will translate it

## 3. Technologies and Libraries
![Screenshot 2023-10-02 204159](https://github.com/EthanFlores1/practice/assets/110417575/6a0b8bc2-b62c-4664-8ab5-1861878598c1)

This entire project was created using the Python programming language. We utilized various neural network architectures such as an autoencoder (artificial neural network) and AlexNet (convolutional neural network). Some of the libraries we used include: PyTorch, TensorFlow, OpenCV, Scikit-learn, Numpy, and Pandas.

## 4. Challenges
Because signatures vary from person to person with no set outline, translating the signature becomes very tedious. There were too much variability in what the signature would look which led to much time and effort being put in to improve the accuracy of the model. Along with this, many algorithms and techniques had to be employed which led to the project becoming very time consuming which was especially tough given the time constraints.

## Author Info
- Aniruddha (mentor)
- Siddharth Vyasabattu
- Melanie Carranza
- Ethan Flores
- Xiang Ding
- Cody Rupp
