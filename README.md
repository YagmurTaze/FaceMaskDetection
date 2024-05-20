# Face-Mask Detector
Face-mask detection on images using Deep Learning and OpenCV

## About Project

This project uses a Deep Neural Network, more specifically a Convolutional Neural Network, to differentiate between images of people with and without masks. The CNN manages to get 
an accuracy of **98% on the training set** and **98% on the test set**. Then the stored weights of this CNN are used to classify as mask or no mask in the images, using OpenCV.

After doing a few preprocessing operations on the image (resizing, converting to numpy array, etc.), it is fed to the model to accomplish this task.

#### Classification Report

<img width="329" alt="results" src="https://github.com/YagmurTaze/FaceMaskDetection/assets/56199172/d9641807-1743-4ba8-90dd-f08abef0835d">

## Examples

### With Mask

<img width="303" alt="example2" src="https://github.com/YagmurTaze/FaceMaskDetection/assets/56199172/96779744-d83c-4045-8f03-45b4dfab3f31">

### Without Mask

<img width="290" alt="example1" src="https://github.com/YagmurTaze/FaceMaskDetection/assets/56199172/c31033ff-5606-4682-8808-a82d918520e8">

## Dataset

The data used can be downloaded through this [link](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset). Data set consists of 7553 RGB images in 2 folders as with_mask and without_mask. Images are named as label with_mask and without_mask. Images of faces with mask are 3725 and images of faces without mask are 3828.



