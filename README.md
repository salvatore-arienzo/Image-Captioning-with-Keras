# Image-Captioning-with-Keras

## Project for Context Aware Security Analitycs @ Unisa, Winter 2019

###  Abstract
  
Image Captioning is the automatic generation of
natural sentences that describe the contents of
a given image. In order to realize this task, has
been used Keras with TensorFlow as backend.
The data used for the project derives from the
Flickr Image dataset, an open dataset obtainable
online. Two types of Neural Network has been
used: a Convolutional Neural Network to extract
features from the images, then a Recurrent Neu-
ral Network as a decoder. The achieved results
are not perfect, but quite acceptable, the gen-
erated captions are always related to the given
image, but sometimes with some mistakes. To
evaluate the accuracy of the model the BLEU
(Bilingual evaluation understudy) metrics and a
custom metric have been used.

### Prerequisites
  
1. Install requirements.txt
2. Download Dataset [here](https://www.kaggle.com/hsankesara/flickr-image-dataset).
3. Download GLove vectors [here](https://www.kaggle.com/watts2/glove6b50dtxt).


