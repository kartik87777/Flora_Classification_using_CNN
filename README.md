# Flora_Classification_using_CNN

Classifying 5 different types of Flowers using Convolutional Neural Networks

I made use of the following flowers to classify:

1. Rose

2. Poppy

3. Lily

4. Iris

5. Daisy

Steps to follow:

1. Create your own Dataset:

Follow the following steps to create your own dataset
  
  a. Open up Google images and search for the images that you wish to download. 
  
  b. Scroll till you feel the number of images are sufficient.
  
  c. Now go to "inspect element" (the source code of that page).
  
  d. Click on Console and there you need to paste the code line by line which is available in js_console.json file.
  
  e. Once the code is entered, a text file is automatically downloded which contains the urls of all the images.
  
  f. Now use the download_images.py file to download the images.


2. Use the Keras and Convolutional Neural Networks for classification.

The "NN" folder contains the Neural Nwetwork Model. The model has been designed for 96*96*3 dimension, meaning that all the input images both for 
training and testing will be resized to 96*96 and 3 represents that the images are RGB.

In order to execute, you first need to execute the train.py file which imports the model from the NN folder and trains the network on the images
taht you have downloaded. Once training is done you can now run classify.py file to classify the images into their respective class. Note that 
the images given to classify.py must not be the ones that were used for training.


For any queries feel free to write at karthik8777@gmail.com
