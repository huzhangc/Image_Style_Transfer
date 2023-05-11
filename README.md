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

In Real_Time_Transfer.ipynb, the file documented the whole process of uploading& preprocessing data, implementing and training the image transformation network with the pretrained vgg16 network, hyperparameter tuning on style weights and training weights, performing image style transfer on content images and outputing the result images and losses. Model of each epoch and trials are saved.(As you can find in Model) 

## Example commands to execute the code
Those two notebooks are originally run on Colab so some path should be adjust if you want to run it locally. Please follow the instructions on the ipynb files to set up the environment and the required dataset. 
Images required to run those two notebooks are included in the images folders in this repo. Pre-trained models for Real_Time_Transfer are included in the models folders. 

## Evaluation
*Real-time Style Transfer

Real-time style transfer has pretty robust performance on different types of content images: landscape, objects, potraits, light, etc. The output images are clear and recognizable. No unusual twists or fragmentation appear in the transfered images. The time for generating the images is fast, with an average around 1.5 seconds. 
<img width="1044" alt="City_transfer_result" src="https://github.com/huzhangc/Image_Style_Transfer/assets/89945246/a4e2b2c9-aeba-4aea-9ca8-d9669a449d0b">
<img width="1046" alt="Beach_transfer_result" src="https://github.com/huzhangc/Image_Style_Transfer/asset<img width="1042" alt="Screen Shot 2023-05-11 at 12 58 21 AM" src="https://github.com/huzhangc/Image_Style_Transfer/assets/89945246/5919cd0a-55ef-4b17-a918-5234c90cbdc4">
<img width="1041" alt="portrait_transfer_result" src="https://github.com/huzhangc/Image_Style_Transfer/assets/89945246/f87d7904-0817-4e40-ace1-c525c7288051">
<img width="1045" alt="sunset_transfer_result" src="https://github.com/huzhangc/Image_Style_Transfer/assets/89945246/823e4ed3-a141-4459-b1e9-baa794dec81e">
<img width="1048" alt="arch_transfer_result" src="https://github.com/huzhangc/Image_Style_Transfer/assets/89945246/9e7e13a2-3366-4f51-bd62-ab7c95c741eb">


