# Defi IA 1.1 - fire detection
# keras-Xception

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## Introduction

A Keras implementation of Xception.
This Work was applied to fire detection

<p align="center">

  <img src="https://github.com/EmiGenin/defis/blob/master/nofire.png" alt ="fire/no fire/start fire" height="100" width="159" hspace="50" title="hover text">
  <img src="https://github.com/EmiGenin/defis/blob/master/startfire.png" alt ="fire/no fire/start fire" height="100" width="133" hspace="50" title="hover text">
  <img src="https://github.com/EmiGenin/defis/blob/master/fire.png" alt ="fire/no fire/start fire" height="100" width="144" hspace="50" title="hover text">
</p>


---

## Quick Start to train a model (input_classification.ipynb)
1. Import the libraries
2. Download the dataset
3. Extract, create a folder and move images in it and create of the label file "classes.txt"
4. Generation of data from paths and labels
5. Definition of parameters
6. Collect images and their classes
7. Data preparation
8. Download of the pre-trained model an tranfer learning
9. Training of the model
10. Reload the pre-trained model with the weights of the last workout and first frozen weights
11. Test the model
	11.1 Download the test dataset
	11.2 Load the model and fix parameters
	11.3 Evaluation of the accuracy and loss
	11.4 Evaluation of the number of correct classification (informative)

```
## How it works
	#1. Download "input_classification.ipynb"
	#2. Connect to google colab with a google account
	#3. Clic on file, import a notebook and go to the path where it have been downloaded. You can also import the notebook by 	      entering the GitHub link
## Explain for other datasets
	#1. Sort your images between the classes you want to test 
	#2. Put each type in a folder with the name of the class  
	#3. At point 2 and 3, change the link of the test dataset path and change the extraction name and type if necessary  
	#4. At point 4, change the name of the folder where the class name should be extract
	#5. At point 6, change the name of dataset	

## Explain for other pre-trained model
	#1. At point 6, change the pre-trained model
	#2. At point 9, put the name of the pre-trained model fixed at point 6
	#3. At point 10, change the name of the result's path to correspond at the right model
	#4. At point 11, Do the same as at point 9 and 10
Attention : the "input_size" have to match with what the model accepts, see at point 1 which input_size for the model
```
---

## Quick Start to only test a model 
1. Import the libraries
2. Downloads
	2.1 Download the test dataset
	2.2 Download the model
3. Creation of "classes.txt"
4. Load the model
5. Generation of data from paths and labels
6. Test on the model
	6.1 Evaluation of the accuracy and the loss
	6.2 Evaluation of the number of correct classifications (informative)

```
## Explain for other datasets
	#1. Sort your images between the classes you want to test 
	#2. Put each type in a folder with the name of the class  
	#3. At point 2.1, change the link of the test dataset path and change the extraction name and type if necessary  
	#4. At point 3, change the name of the folder where the class name should be extract
	#5. At point 4, change the name of dataset_path	
```
---
## The test environment is
    - Python 3.6.8
    - Keras 2.2.5
    - tensorflow 1.15.0
