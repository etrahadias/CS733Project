# Accessible Beekeeping: Captioning Diseased Honey Bee Brood Frames with Deep Learning

## CS 733 Final Project

Author: Elizabeth Trahadias

Email: etrah001@odu.edu

## Overview
 
Beekeeping is a visual activity, and it is important to be able to visually inspect frames to detect and assess certain diseases early. Certain diseases in honey bee hives have distinct visual symptoms that separate them from others.

The purpose of this project is to make the early detection of brood diseases in honey bee hives accessible to visually impaired beekeepers by creating an image captioning model that generates descriptive captions of diseased brood frames. 

I encourage you to check out [this](https://youtu.be/6rjT2sDkFY0) notebook first. This notebook puts together all of the models and includes text-to-speech to read the final caption if the image is unheatlhy!

## Repository and Code Details

### Model Training
In the *model_training* folder, you will find the following Jupyter Notebooks that show how I trained the different models I used to create my final captioning prototype. Please be advised that if you run these files, you will also be training the models, and these files take a long time to run. 

* Notebook that displays the whole system: CS733_Project_Bee_Image_Captioner_Prototype-Final-V2.ipynb
* Notebook to train the CNNs for image classification: CS733_Project_VisionEncoderDecoder_ImageCaptioning_Final.ipynb
* Notebook to fine-tune masked language models: CS733_Project_FineTunedLanguageModelsDomainSpecific.ipynb
* Notebook for image captioning fine-tuning: CS733_Project_VisionEncoderDecoder_ImageCaptioning_Final.ipynb
* Notebook for image captioning fine-tuning (SHORTER VERSION): CS733_Project_VisionEncoderDecoder_ImageCaptioning_Final_SHORTER.ipynb


### Saved Models

Due to size limitations, I was not able to upload to GitHub all of the saved versions of my fine-tuned models. The only model I was able to upload was the 'best_unhealthy_cnn_final_version.h5'. The other models listed below are available at the links below in my Google Drive.

* CNN model healthy/unhealthy: 'cnn_healthy_vs_unhealthy_final.h5' (available [here](https://drive.google.com/file/d/1zGCAvq8trIL1VNmRNZuh_1d4ySoXTF29/view?usp=share_link))
* CNN type of disease: 'best_unhealthy_cnn_final_version.h5' (available in GitHub)
* Best image captioning model: 'vit-scibert-final' (available [here](https://drive.google.com/drive/folders/1N6pz-oNprYrWAuJQ7363zaYVF2AM6HFe?usp=sharing))

With the files above, you should be able to run the final image captioning model in the notebook named **CS733_Project_Bee_Image_Captioner_Prototype-Final-V2.ipynb**

* Fine-tuned SciBERT: 'scibert-bees-final' (almost 5 GB in size, available upon request)

### Dataset

The data set and respective captions for the unhealthy images are located on my Google Drive. For the submission of my project, the link to the folders with my data set are included for your convenience in my Canvas submission. The links with my image sources are also available in these folders, and my manually generated captions are available in each of the data set folders.

### Final Product

Here, you can see how the images flow from the beginning of the process all the way to the end of the process, which is where a descriptive caption is generated.

**The notebook that displays the whole system is named as follows: CS733_Project_Bee_Image_Captioner_Prototype-Final-V2.ipynb**

There is also a Google Colab version of this notebook that includes text-to-speech! I encourage you to check out [this notebook](https://colab.research.google.com/drive/1c9vUf9ad97ZSMe_oAMV2HyMCc908XAdG?usp=sharing). It is also what I demo in my video.

## Video Presentation

The video presentation explaining my project and results can be found [here](https://youtu.be/6rjT2sDkFY0).


