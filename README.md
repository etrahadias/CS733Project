# Accessible Beekeeping: Captioning Diseased Honey Bee Brood Frames with Deep Learning

## CS 733 Final Project

Author: Elizabeth Trahadias

Email: etrah001@odu.edu

## Overview
 
Beekeeping is a visual activity, and it is important to be able to visually inspect frames to detect and assess certain diseases early. Certain diseases in honey bee hives have distinct visual symptoms that separate them from others.

The purpose of this project is to make the early detection of brood diseases in honey bee hives accessible to visually impaired beekeepers by creating an image captioning model that generates descriptive captions of diseased brood frames. 

## Repository and Code Details

### Model Training
In the *model_training* folder, you will find the following Jupyter Notebooks that show how I trained the different models I used to create my final captioning prototype. Please be advised that if you run these files, you will also be training the models, and these files take a long time to run. I have also included the .pdf versions of the notebooks with all of the code run in case you want to see just the output and my notes.

* CNNs:
* Fine-tuning BERT:
* Image captioning fine-tuning:

### Saved Models

In this folder, there are a series of saved models so a user can use these models rather than train the models themselves.

* CNN model healthy/unhealthy
* CNN type of disease
* Fine tune BERT
* Best image captioning model

### Dataset

This folder has all of the images and captions.

### Final Product

This folder has a Jupyter Notebook that reads in all of the best models from the models available in the *saved_models* folder. Here, you can see how the images flow from the beginning of the process all the way to the end of the process, which is where a descriptive caption is generated.

## Video Presentation

The video presentation explaining my project and results can be found [here]().


