# Image_Style_Transfer
DS301_Final_Project

## Project Description
Image style transfer is a technique that preserves the content of an image while applying the style of another image onto it. This method relies on a neural network to learn the features that capture the style and content of the input images, which are then used to create a new image that merges the content of one image with the style of the other.

In this project, we aim to examine and evaluate 2 popular algorithms of image style transfer:
* Neural Style Transfer
* Real-time Style Transfer

## Project Framework
<img width="512" alt="image" src="https://github.com/huzhangc/Image_Style_Transfer/assets/98297644/2ea65b3a-bd95-4940-9cdc-041024b52e40">

## Code Structure
This repo contains the 2 google colab notebook, and we suggesting using GPU to execute those notebooks.
* Neural_Style_Transfer.ipynb
* Real_Time_Transfer.ipynb

In Real_Time_Transfer.ipynb, the file documented the whole process of uploading& preprocessing data, training and implementing the image transformation network with the pretrained vgg16 network, hyperparameter tuning on style weights and training weights, performing image style transfer on content images and outputing the results. Model of each epoch and trials are saved.(As you can find in Model) 

## Example commands to execute the code
Those two notebooks are originally run on Colab so some path should be adjust if you want to run it locally.
Images required to run those two notebooks are included in the images folders in this repo.

## Evaluation
