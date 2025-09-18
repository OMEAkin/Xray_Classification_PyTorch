# Xray_Classification_PyTorch
Project from Datacamp
Task: Classification + Fine-Tuning Deep Learning (ResNet-18) Model 

## Background
Pneumonia is one of the leading respiratory illnesses worldwide, and its timely and accurate diagnosis is essential for effective treatment. Manually reviewing chest X-rays is a critical step in this process, and AI can provide valuable support by helping to expedite the assessment. 

## Goal
Test the ability of a deep learning model to distinguish pneumonia cases from normal images of lungs in chest X-rays. Fine-tune a pre-trained convolutional neural network (ResNet-18 model) and classify X-ray images into two categories: normal lungs and those affected by pneumonia. 

Why fine-tuning? Can leverage already trained weights, train an accurate classifier faster, and with fewer resources.

## The Data
A dataset of preprocessed chest X-rays for use with a ResNet-18 model. Initially, there are 150 training images and 50 testing images for each category, NORMAL and PNEUMONIA (300 and 100 in total). Later, 50 images are randomly selected from the training images and used as validation images. 

## Model
Pretrained ResNet-18 with only the weights of the last layer being adjusted. Fine-tuned for 5 epochs.
