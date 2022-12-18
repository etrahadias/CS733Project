# Accessible Beekeeping: Captioning Diseased Honey Bee Brood Frames with Deep Learning

## CS 733 Final Project

Author: Elizabeth Trahadias

Email: etrah001@odu.edu

## Overview
 
Beekeeping is a visual activity, and it is important to be able to visually inspect frames to detect and assess certain diseases early. Certain diseases in honey bee hives have distinct visual symptoms that separate them from others.

The purpose of this project is to make the early detection of brood diseases in honey bee hives accessible to visually impaired beekeepers by creating an image captioning model that generates descriptive captions of diseased brood frames. 

## Repository and Code Details

### Model Training
In the *model_training* folder, you will find the following Jupyter Notebooks that show how I trained the different models I used to create my final captioning prototype. Please be advised that if you run these files, you will also be training the models, and these files take a long time to run. 

* Notebook to train the CNNs for image classification: CS733_Project_VisionEncoderDecoder_ImageCaptioning_Final.ipynb
* Notebook to fine-tune masked language models: CS733_Project_FineTunedLanguageModelsDomainSpecific.ipynb
* Notebook for image captioning fine-tuning: CS733_Project_VisionEncoderDecoder_ImageCaptioning_Final.ipynb


### Saved Models

In this folder, there are a series of saved models so a user can use these models rather than train the models themselves.

* CNN model healthy/unhealthy: 'cnn_healthy_vs_unhealthy_final.h5'
* CNN type of disease: 'best_unhealthy_cnn_final_version.h5'
* Fine-tuned SciBERT: 'scibert-bees-final'
* Best image captioning model: 'vit-scibert-final'

### Dataset

The data set and respective captions for the unhealthy images are located on my Google Drive. For the submission of my project, the link to the folders with my data set are included for your convenience. They have been shared with you.

### Final Product

This folder has a Jupyter Notebook that reads in all of the best models from the models available in the *saved_models* folder. Here, you can see how the images flow from the beginning of the process all the way to the end of the process, which is where a descriptive caption is generated.

**The notebook that displays the whole system is named as follows: CS733_Project_Bee_Image_Captioner_Prototype-Final-V2.ipynb**

There is also a Google Colab version of this notebook that includes text-to-speech! I encourage you to check out [this notebook](https://colab.research.google.com/drive/1c9vUf9ad97ZSMe_oAMV2HyMCc908XAdG?usp=sharing). It is also what I demo in my video.

## Video Presentation

The video presentation explaining my project and results can be found [here]().


