# Signature Detection, Extraction, and Translation
![Screenshot 2023-10-02 201703](https://github.com/acmucsd-projects/su23-ai-team-1/assets/110417575/0642fc84-19d8-4bea-a495-d7cf430f11fd)
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
![Screenshot 2023-10-02 204159](https://github.com/acmucsd-projects/su23-ai-team-1/assets/110417575/908a226d-488e-4f11-b583-d18de999485b)

This entire project was created using the Python programming language. We utilized various neural network architectures such as an autoencoder (artificial neural network) and AlexNet (convolutional neural network). Some of the libraries we used include: PyTorch, TensorFlow, OpenCV, Scikit-learn, Numpy, and Pandas.

## 4. Challenges
Because signatures vary from person to person with no set outline, translating the signature becomes very tedious. There were too much variability in what the signature would look which led to much time and effort being put in to improve the accuracy of the model. Along with this, many algorithms and techniques had to be employed which led to the project becoming very time consuming which was especially tough given the time constraints.

## Author Info
- Aniruddha (mentor)
- Siddharth Vyasabattu [Linkedin](https://www.linkedin.com/in/xiang-ding-) | [Github](https://github.com/fanhh)
- Melanie Carranza
- Ethan Flores [LinkedIn](https://www.linkedin.com/in/ethan-flores-0317b9283) | [Github](https://github.com/EthanFlores1)
- Xiang Ding [LinkedIn](https://www.linkedin.com/in/xiang-ding-) | [Github](https://github.com/fanhh)
- Cody Rupp [LinkedIn](https://www.linkedin.com/in/codyprupp) | [GitHub](https://www.github.com/codyprupp)
