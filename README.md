# Image-captioning

# Dataset and its structure
Image captioning project on Flickr8K dataset
Flickr_8K dataset, all the images of training, validation and test set are in one folder. It contains 3 different files i.e Flickr_8k.trainImages.txt, Flickr_8k.testImages.txt , Flickr_8k.devImages.txt  corresponding to each type of dataset i.e train, test and validation set, each file having file_name of images conatined in each dataset. 
In Flick8k, Flickr_8k.trainImages.txt file contains file_ids of images in training set. Name of image file is its image id.
All the images are in same folder. So to parse images of training dataset, first read trianImages.txt file, read line by line image id and load corresponding image from image dataset folder.
Each image is given 5 different captions by 5 different humans. This is because an image can be described in multiple ways.
These captions are stored in 'Flickr8k.token.txt'. Each line of file contains a caption corresponding to an image. And for one image, there are 5 lines representing 5 captions for one image file.

# Research papers and resources followed
1. https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/
2. https://www.kaggle.com/code/mabsiddiquesanjan/thesis
