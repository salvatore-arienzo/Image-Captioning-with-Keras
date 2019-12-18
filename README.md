# Image-Captioning-with-Keras

## Project for Context Aware Security Analitycs @ Unisa, Winter 2019

###  Abstract
  
Image Captioning is the automatic generation of natural sentences that describe the contents of a given image. In order to realize this task, has been used Keras with TensorFlow as backend. The data used for the project derives from the Flickr Image dataset, an open dataset with around 30k images of both people and animals obtainable online. Two types of Neural Network have been used: a Convolutional Neural Network to extract features from images, then a Recurrent Neural Network as a decoder. The Recurrent Neural Networks gives as result a probability of match for each word: these probabilities are then used by a greedy algorithm, that given a new image as input, build the caption iteratively, choosing, for each iteration, the word with the higher probability. The achieved results are not perfect, but quite acceptable, the generated captions are always related to the given image, often subject, object and action are recognized very well, but sometimes there are some mistakes. To evaluate the accuracy of the model the BLEU (Bilingual evaluation understudy) metrics and a custom metric based on the number of words in common between the auto-generated caption and the reference captions have been used. Some examples of auto-generated captions (both correct and uncorrect) are listed below.

<p align="center">
<img width="300" height="300" src="https://github.com/salvatore-arienzo/Image-Captioning-with-Keras/blob/master/ppt/Esempio%201.png"> <img width="300" height="300" src="https://github.com/salvatore-arienzo/Image-Captioning-with-Keras/blob/master/ppt/Esempio%202.png">
</p>

<p align="center">
<img width="300" height="300" src="https://github.com/salvatore-arienzo/Image-Captioning-with-Keras/blob/master/ppt/Example%204.png"> <img width="300" height="300" src="https://github.com/salvatore-arienzo/Image-Captioning-with-Keras/blob/master/ppt/example%203.png">
</p>

<p align="center">
<img align="center" width="300" height="300" src="https://github.com/salvatore-arienzo/Image-Captioning-with-Keras/blob/master/ppt/cooking.png"> <img align="center" width="300" height="300" src="https://github.com/salvatore-arienzo/Image-Captioning-with-Keras/blob/master/ppt/GroupOfPeople.png">
</p>

<p align="center">
<img align="center" width="300" height="300" src="https://github.com/salvatore-arienzo/Image-Captioning-with-Keras/blob/master/ppt/ult2.png"> <img align="center" width="300" height="300" src="https://github.com/salvatore-arienzo/Image-Captioning-with-Keras/blob/master/ppt/ult4.png">
</p>

<p align="center">
<img align="center" width="300" height="300" src="https://github.com/salvatore-arienzo/Image-Captioning-with-Keras/blob/master/ppt/snowimg.png"> <img align="center" width="300" height="300" src="https://github.com/salvatore-arienzo/Image-Captioning-with-Keras/blob/master/ppt/Example%205.png"> 
</p>

### Prerequisites
  
1. Install requirements.txt
2. Download Dataset [here](https://www.kaggle.com/hsankesara/flickr-image-dataset).
3. Download GLove vectors [here](https://www.kaggle.com/watts2/glove6b50dtxt).

### References

Some references: [Medium](https://medium.com/@faizanmustafa75/keras-implementation-of-image-captioning-model-3a7ab68e67d4), [towardsdatascience](https://towardsdatascience.com/image-captioning-with-keras-teaching-computers-to-describe-pictures-c88a46a311b8) and [machinelearningmastery](https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/). For full references and details about the project read this short [article](https://github.com/salvatore-arienzo/Image-Captioning-with-Keras/blob/master/Image%20Captioning%20with%20Keras.pdf).
