# Boob Locator
Finds boobs in an image and encloses a bounding box with confidence probability
This repo contains the official code, data and sample outputs for our model that locates the corrdianates of boobs in any NSFW image.
Please see the accuracy numbers to see the details.

## Motivation
This is a simple implementation helping you to 
* tag all your images for those containing boobs.( partially covered or fully exposed ) 
* crop out video that has any boobs ( potentially NSFW ) 
* Pixellate the images with boobs in them - NSFW images 

## Disclaimer

This repository is intended for eductional purposes, and to allow people to contribute towards/improve the model's accuracy codebase. While we donot encourage the download of the whole repository and data for training, 
we do provide the option for it to be trained into a custom model that you can deploy locally.
See `prerequisites` for more information on training your own model.

## Built With

* Python/PyTorch
* Yolov5


## Prerequisites

* You will need to download the entire images(data) / labels(annotations) folder  ( This runs into GB's and is hosted in anonymous serers )
* You will need a powerful GPU and good healthy computer
* You might have to run the training process for a few hours ( almost 20 + hours ) depending on the GPU that you have.
* preferably an NVDIA GPU card 

## Dependencies

* see the requirements.txt file 

## Updates : 
* 07/10/2022 Start demo model / MVP 
* Code release
* Sample Implementation code release 


## TODO:

