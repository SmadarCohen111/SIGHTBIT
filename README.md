# SIGHTBIT

# Home assigenment

The algorithm uses images from COCO dataset and detect the sky area from the image.
after the wanted detection (the sky area), we import data on the image and data on the mask, compare, calculate and bring the valid information for removing the sky line.
after all that is done, we create a new data set that full with the images and information we took from COCO dataset without the sky parts on the image and the inforemation about rhe iamge.
The purpose of this algorithm is to create a new data set from COCO dataset without the sky ROI.


the project uses 10 libraries: detectron2, PYtorch, openCV, numpy, google.colab, glob, requests,json, cv2, numpyencoder 

we use the configuration zoo model of detectron2, and Panoptic Segmentation, because its ability to detect the background.
images without the background sky will not be cut and pictures with a lot of sky area will almost disappear and respectively the images sizes will be very small.


## Installation

for this project you will need those enviorments:

access to google drive <br />
google colaboratory / Jupyter notebook <br />
Python <br />
framework: Detectron2 <br />

open the project by google colaboratory and connect the GPU.

After the connection to the GPU, you can ran all the cells in the colab and you will see the images without the sky parts at the end of the algorithm, and they will be saved in dirctory at your drive.

## licsence
    detectron2 licsence, requests, openCV = Apache License 2.0
    numpyencoder, glob = MIT License 
    pytorch, numpy / scipy, google.colab = 3 - BSD


## Visuals

  ![image](https://user-images.githubusercontent.com/49597158/125208641-70318080-e29c-11eb-9be4-8e8679fc9d5a.png)
  ![image](https://user-images.githubusercontent.com/49597158/125208656-7e7f9c80-e29c-11eb-9178-4b7dd1960fe7.png)
  ![image](https://user-images.githubusercontent.com/49597158/125208667-92c39980-e29c-11eb-9d28-e3376e72e0ff.png)


 
 
 





