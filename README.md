# Defi IA 1.1 - fire detection
# keras-Xception

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## Introduction

A Keras implementation of Xception.
This Work was applied to fire detection

<p align="center">

  <img src="https://github.com/EmiGenin/defis/blob/master/nofire.png" alt ="fire/no fire/start fire" height="100" width="159" title="hover text">
  <img src="https://github.com/EmiGenin/defis/blob/master/startfire.png" alt ="fire/no fire/start fire" height="100" width="133" title="hover text">
  <img src="https://github.com/EmiGenin/defis/blob/master/fire.png" alt ="fire/no fire/start fire" height="100" width="144" title="hover text">
</p>


---

## Quick Start
1. Import the libraries
2. Downloads
	2.1 Download the test dataset
	2.2 Download the model
3. Creation of "classes.txt"
4. Load the model
5. Generation of data from paths and labels
6. Test on the model
	6.1 Evaluation of the accuracy and the loss
	6.2 Evaluation of the number of correct classifications

```
## How it works after importing the libraries
	#1. Download dataset and the model :
	wget https://github.com/EmiGenin/defis/releases/download/defi11-model/imgs_test_2.tar
	wget https://github.com/EmiGenin/defis/releases/download/defi11-model/classification_final.h5
	extract imgs_test_2
	#2. Extract the class names
	#3. Load the model, fix the model path and dataset path
	#4. Generate the data from paths and labels to be prepared for the test
	#5. The tests on the model are done 
		#by the evaluation of the accuracy and the loss 
		#by the numbre of correct classifications dirrectly mesured on the dataset

## Explain the Training for other datasets
	#1. Sort your images between the classes you want to test 
	#2. Put each type in a folder with the name of the class  
	#3. At point 2.1, change the link of the test dataset path and change the extraction name and type if necessary  
	#4. At point 3, change the name of the folder where the class name should be extract
	#5. At point 4, change the name of dataset_path	

## The test environment is
    - Python 3.6.8
    - Keras 2.2.5
    - tensorflow 1.15.0
