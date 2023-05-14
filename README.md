# captcha_image

 # Abstract

Today, captcha is a common method for preventing automated programmes from accessing
online resources like websites, emails, etc. Captcha is an acronym for Completely Automated
Public Turing test to differentiate between computers and humans. It is a challenge-response
test that determines whether the user is a person or a computer. There are various varieties
of captcha techniques, including audio-based, text-based, and image-based, etc. Image-based
captchas, in which the user is required to recognise and enter a combination of letters and
numbers displayed in an image, are extensively used among these techniques.In this endeavor,
we’ve employed deep learning techniques to improve the precision of alphanumeric-based
captcha solving. We used a real-time dataset to make predictions with Convolutional Neural
Network (CNN), Deep Neural Network (DNN), Combination of CNN and Recurrent Neural
Network (RNN), and Neural Network with Nested Design model. Tensorflow, Keras, OCR,
OpenCV, and Tkinter were used to create the model, and Tkinter is used for the image selection user interface.We used a dataset from Kaggle in which all the images are five-letter words
that may contain digits, and noise (blur and a line) has been applied to the images. The images
are PNGs measuring 200 by 50 pixels. We divided the dataset into train and test sets, calculated
the accuracy, and provided an image captcha prediction. The goal of the project is to increase
the accuracy of the model by comparing the outcomes of various deep learning techniques.This
project aims to determine which deep learning technique provides the highest level of accuracy
for solving alphanumeric-based captchas by comparing the accuracy of various deep learning
techniques. This project’s outcomes can be utilized to improve the security of other captcha
techniques.
