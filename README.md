# Traffic-Light-Classification

In this project, we have used knowledge of computer vision techniques to build a classifier for images of traffic lights! We were given a dataset of traffic light images in which one of three lights is illuminated: red, yellow, or green.
In this notebook, we pre-processed these images, extract features that helped us distinguish the different types of images, and use those features to classify the traffic light images into three classes: red, yellow, or green. The tasks will be broken down into a few sections:
Loading and visualizing the data. The first step in any classification task is to be familiar with your data; you'll need to load in the images of traffic lights and visualize them!
Pre-processing. The input images and output labels need to be standardized. This way, you can analyze all the input images using the same classification pipeline.
Feature extraction. Next, we extracted brightness feature from each image that will help distinguish and eventually classify these images.
Classification and visualizing error. Finally, we wrote one function that uses your features to classify any traffic light image. This function take in an image and output a label. We have also written a code to determine the accuracy of our classification model.
