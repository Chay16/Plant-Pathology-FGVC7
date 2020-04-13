# Plant-Pathology-FGVC7
Kaggle competition [‘Plant Pathology Challenge’](https://www.kaggle.com/c/plant-pathology-2020-fgvc7/overview) for FGVC7 workshop at CVPR 2020 in Seattle, Washington State

## Problem Statement

Misdiagnosis of the many diseases impacting agricultural crops can lead to misuse of chemicals leading to the emergence of resistant pathogen strains, increased input costs, and more outbreaks with significant economic loss and environmental impacts. Current disease diagnosis based on human scouting is time-consuming and expensive, and although computer-vision based models have the promise to increase efficiency, the great variance in symptoms due to age of infected tissues, genetic variations, and light conditions within trees decreases the accuracy of detection.

## Specific Objectives

Objectives of ‘Plant Pathology Challenge’ are to train a model using images of training dataset to 
- Accurately classify a given image from testing dataset into different diseased category or a healthy leaf
- Accurately distinguish between many diseases, sometimes more than one on a single leaf
- Deal with rare classes and novel symptoms
- Address depth perception—angle, light, shade, physiological age of the leaf
- Incorporate expert knowledge in identification, annotation, quantification, and guiding computer vision to search for relevant features during learning.

## Repository Objective

The goal of this repository is to regroup all the script created and used to adress the second task of ‘Plant Pathology Challenge’. [PyTorch](https://github.com/pytorch/pytorch) has been choosen to be the framework used in this repository
